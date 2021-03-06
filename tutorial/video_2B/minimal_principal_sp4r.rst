Example :math:`G=Sp(4,\mathbb R)`
----------------------------------

Now lets find all representations with infinitesimal character :math:`\rho` ::

   atlas> G:Sp(4,R)
   Variable G: RealForm (overriding previous instance, which had type RealForm)
   atlas> G
   Value: connected split real group with Lie algebra 'sp(4,R)'
   atlas> set parameters=all_parameters_gamma (G, rho(G))
   Variable parameters: [Param]
   atlas> rho(G)
   Value: [ 2, 1 ]/1
   atlas> #parameters
   Value: 18
   atlas> void: for p in parameters do prints(p) od
   final parameter (x=0,lambda=[2,1]/1,nu=[0,0]/1)
   final parameter (x=1,lambda=[2,1]/1,nu=[0,0]/1)
   final parameter (x=2,lambda=[2,1]/1,nu=[0,0]/1)
   final parameter (x=3,lambda=[2,1]/1,nu=[0,0]/1)
   final parameter (x=4,lambda=[2,1]/1,nu=[1,-1]/2)
   final parameter (x=5,lambda=[2,1]/1,nu=[0,1]/1)
   final parameter (x=5,lambda=[2,2]/1,nu=[0,1]/1)
   final parameter (x=6,lambda=[2,1]/1,nu=[0,1]/1)
   final parameter (x=6,lambda=[2,2]/1,nu=[0,1]/1)
   final parameter (x=7,lambda=[2,1]/1,nu=[2,0]/1)
   final parameter (x=7,lambda=[3,1]/1,nu=[2,0]/1)
   final parameter (x=8,lambda=[2,1]/1,nu=[2,0]/1)
   final parameter (x=8,lambda=[3,1]/1,nu=[2,0]/1)
   final parameter (x=9,lambda=[2,1]/1,nu=[3,3]/2)
   final parameter (x=10,lambda=[2,1]/1,nu=[2,1]/1)
   final parameter (x=10,lambda=[3,1]/1,nu=[2,1]/1)
   final parameter (x=10,lambda=[2,2]/1,nu=[2,1]/1)
   final parameter (x=10,lambda=[3,2]/1,nu=[2,1]/1)
   atlas>

There are 18 representations with infinitesimal character
:math:`\rho`. The last four parameters have :math:`K\backslash G/B`
element ``x=10``. They correspond to the four priincipal series
attached to the split Cartan.

More generally if :math:`G(\mathbb R)` is split of rank :math:`n`, the
number of minimal principal series of infinitesimal character
:math:`rho` corresponds to the set of characters of the split cartan
:math:`({\mathbb R}^{\times}) ^n` : ``{(lambda,nu)}``. And up to the
Weyl group, ``nu=rho``. So there are :math:`2^n` choices of ``lambda``
which is a character of :math:`({\mathbb Z}_2)^n`.

In this case the rank is :math:`2`, so there are four, namely the last
four representations in the above list.

Let us make a separate list for them::

   atlas> set ps=[parameters[14],parameters[15],parameters[16],parameters[17]]
   Variable ps: [Param]
   atlas> void: for p in ps do prints(p) od
   final parameter (x=10,lambda=[2,1]/1,nu=[2,1]/1)
   final parameter (x=10,lambda=[3,1]/1,nu=[2,1]/1)
   final parameter (x=10,lambda=[2,2]/1,nu=[2,1]/1)
   final parameter (x=10,lambda=[3,2]/1,nu=[2,1]/1)
   atlas>

These parameters are all principal series. How do we tell them apart?

Each one is giving a character of the split Cartan. They have the same
``nu`` and same ``x=10`` and a different lambda. Each lambda is a
character of :math:`{\mathbb Z}_2 \times {\mathbb Z}_2`. In other
words they are in :math:`X^*/2X^*`.

To know which is which we look at their ``tau`` invariant::

   atlas> void: for p in ps do prints(p," ",tau(p)) od
   final parameter (x=10,lambda=[2,1]/1,nu=[2,1]/1) [0,1]
   final parameter (x=10,lambda=[3,1]/1,nu=[2,1]/1) [1]
   final parameter (x=10,lambda=[2,2]/1,nu=[2,1]/1) []
   final parameter (x=10,lambda=[3,2]/1,nu=[2,1]/1) [0]
   atlas>

So the ``tau`` invariant is big for the element ``ps[0]``, which means
the irreducible is a small representation. In fact that is the trivial
representation. In contrast, the smallest tau invariant, the empty
set, correspnding to the element ``ps[2]`` gives the biggest
representation. In this case this is the irreducible principal
series. The other two, namely the elements ``ps[1]`` and ``ps[3]`` on
the list, correspond to the long and short roots respectively. So each
of them are distinquished by their tau invariant.

Now lets look at the composition series of the standard module
containing the trivial representation ::

   atlas> p:ps[0]
   Variable p: Param
   atlas> show(composition_series(I(p)))
   1*J(x=0,lambda=[2/1,1/1],nu=[0/1,0/1])
   1*J(x=1,lambda=[2/1,1/1],nu=[0/1,0/1])
   2*J(x=4,lambda=[2/1,1/1],nu=[1/2,-1/2])
   1*J(x=5,lambda=[2/1,1/1],nu=[0/1,1/1])
   1*J(x=6,lambda=[2/1,1/1],nu=[0/1,1/1])
   1*J(x=7,lambda=[2/1,1/1],nu=[2/1,0/1])
   1*J(x=8,lambda=[2/1,1/1],nu=[2/1,0/1])
   1*J(x=9,lambda=[2/1,1/1],nu=[3/2,3/2])
   1*J(x=10,lambda=[2/1,1/1],nu=[2/1,1/1])
   atlas>

This standard module is the sum of all the above irreducibles with
certain multiplicities (note there is one that occurs with
multiplicity 2). The last irreducible is the trivial representation.
This is the biggest composition series. It is the most reducible
principal series, which you can detect by its tau invariant.

On the other hand the empty tau invariant says that the representation
is irreducible::

   atlas> p:ps[2]
   Variable p: Param (overriding previous instance, which had type Param)
   atlas> show(composition_series(I(p)))
   1*J(x=10,lambda=[2/1,2/1],nu=[2/1,1/1])
   atlas>

