.. _hecke.at_index:

hecke.at Function Index
=======================================================
|



Functions

.. list-table::
   :widths: 10 20
   :header-rows: 1

   * - Function
     - Argument(s) -> Results
   * - :ref:`\=_KGB_pair(x,y),_KGB_pair(z,w)->bool1`
     - ``KGB_pair(x,y), KGB_pair(z,w)->bool``
   * - :ref:`\!=_KGB_pair(x,y),_KGB_pair(z,w)->bool1`
     - ``KGB_pair(x,y), KGB_pair(z,w)->bool``
   * - :ref:`y_gen_extparam(ic,,gamma,lambda,,,,omega,,)->kgbelt_gen1`
     - ``ExtParam(ic,,gamma,lambda,,,,omega,,)->KGBElt_gen``
   * - :ref:`y_gen_param_p->kgbelt_gen1`
     - ``Param p->KGBElt_gen``
   * - :ref:`index_kgb_pair_xy,_[kgb_pair]_xy_pairs->int1`
     - ``KGB_pair xy, [KGB_pair] xy_pairs->int``
   * - :ref:`find_pair_(kgb_pair,[kgb_pair])_p->bool1`
     - ``(KGB_pair,[KGB_pair]) p->bool``
   * - :ref:`add_pair_kgb_pair_xy,_[kgb_pair]_xy_pairs->[kgb_pair]1`
     - ``KGB_pair xy, [KGB_pair] xy_pairs->[KGB_pair]``
   * - :ref:`index_extparam_ep,_[kgb_pair]_xy_pairs->int1`
     - ``ExtParam Ep, [KGB_pair] xy_pairs->int``
   * - :ref:`neighbors_int_j,_extparam_ep->[extparam]1`
     - ``int j, ExtParam Ep->[ExtParam]``
   * - :ref:`kgb_sort_[kgbelt]_v->[kgbelt]1`
     - ``[KGBElt] v->[KGBElt]``
   * - :ref:`x_sort_[kgb_pair]_v->[kgb_pair]1`
     - ``[KGB_pair] v->[KGB_pair]``
   * - :ref:`xy_neighbors_int_j,extparam(ic,delta,gamma,lambda,theta,g,l,omega,tau,t):e->[kgb_pair]1`
     - ``int j,ExtParam(ic,delta,gamma,lambda,theta,g,l,omega,tau,t):E->[KGB_pair]``
   * - :ref:`xy_neighbors_int_j,_mat_delta,param_p,_ratvec_g->[kgb_pair]1`
     - ``int j, mat delta,Param p, ratvec g->[KGB_pair]``
   * - :ref:`xy_neighbors_int_j,_mat_delta,_ratvec_gamma,_ratvec_g,_[kgb_pair]_xy_pairs->[kgb_pair]1`
     - ``int j, mat delta, ratvec gamma, ratvec g, [KGB_pair] xy_pairs->[KGB_pair]``
   * - :ref:`generate_subspace_int_j,_int_k,_mat_delta,_ratvec_gamma,_ratvec_g,_kgb_pair(x,y)->[kgb_pair]1`
     - ``int j, int k, mat delta, ratvec gamma, ratvec g, KGB_pair(x,y)->[KGB_pair]``
   * - :ref:`generate_subspace_int_i,_int_j,_extparam_e->[kgb_pair]1`
     - ``int i, int j, ExtParam E->[KGB_pair]``
   * - :ref:`generate_subspace_int_j,_mat_delta,_ratvec_gamma,_ratvec_g,_kgb_pair_p->[kgb_pair]1`
     - ``int j, mat delta, ratvec gamma, ratvec g, KGB_pair p->[KGB_pair]``
   * - :ref:`generate_subspace_int_i_,extparam_e->[kgb_pair]1`
     - ``int i ,ExtParam E->[KGB_pair]``
   * - :ref:`decompose_int_i,_int_j,_mat_delta,_[param]_b,_ratvec_g->([[kgb_pair]],int,[int])1`
     - ``int i, int j, mat delta, [Param] B, ratvec g->([[KGB_pair]],int,[int])``
   * - :ref:`sign_2i12_int_j,_extparam_e,_extparam_f->int2`
     - ``int j, ExtParam E, ExtParam F->int``
   * - :ref:`sign_2i12_old_int_j,extparam_e,extparam_f->int2`
     - ``int j,ExtParam E,ExtParam F->int``
   * - :ref:`sign_2r21_int_j,_extparam_e,_extparam_f->int2`
     - ``int j, ExtParam E, ExtParam F->int``
   * - :ref:`sign_2ci_int_j,extparam_e->int2`
     - ``int j,ExtParam E->int``
   * - :ref:`sign_2cr_int_j,extparam_e->int2`
     - ``int j,ExtParam E->int``
   * - :ref:`signs_1i1_int_j,_extparam_e,_extparam_e1,_extparam_f->(int,int)2`
     - ``int j, ExtParam E, ExtParam E1, ExtParam F->(int,int)``
   * - :ref:`hecke_row_int_j,_mat_delta,_ratvec_gamma,_ratvec_g,_kgb_pair_pair,_[kgb_pair]_basis->[poly]1`
     - ``int j, mat delta, ratvec gamma, ratvec g, KGB_pair pair, [KGB_pair] basis->[poly]``
   * - :ref:`hecke_row_int_j,_extparam(,delta,gamma,,,g,,,,):e,_[kgb_pair]_basis->[poly]1`
     - ``int j, ExtParam(,delta,gamma,,,g,,,,):E, [KGB_pair] basis->[poly]``
   * - :ref:`hecke_matrix_int_j,_mat_delta,_ratvec_gamma,_ratvec_g,[kgb_pair]_basis->poly_mat1`
     - ``int j, mat delta, ratvec gamma, ratvec g,[KGB_pair] basis->poly_mat``
   * - :ref:`quadratic_poly_mat_m,_int_length,_bool_show->bool1`
     - ``poly_mat M, int length, bool show->bool``
   * - :ref:`braid_poly_mat_m,poly_mat_n,_int_length,bool_show->bool1`
     - ``poly_mat M,poly_mat N, int length,bool show->bool``
   * - :ref:`braid_poly_mat_m,poly_mat_n,_int_length->bool1`
     - ``poly_mat M,poly_mat N, int length->bool``
   * - :ref:`test_hecke_int_i,_int_j,mat_delta,_ratvec_gamma,_ratvec_g,_[kgb_pair]_basis->bool1`
     - ``int i, int j,mat delta, ratvec gamma, ratvec g, [KGB_pair] basis->bool``
   * - :ref:`test_hecke_int_i,_int_j,_mat_delta,_ratvec_gamma,_[kgb_pair]_basis->bool1`
     - ``int i, int j, mat delta, ratvec gamma, [KGB_pair] basis->bool``
   * - :ref:`test_hecke_int_i,_int_j,_mat_delta,_[param]_b,_ratvec_g->bool1`
     - ``int i, int j, mat delta, [Param] B, ratvec g->bool``
   * - :ref:`test_hecke_int_i,_int_j,_mat_delta,_[param]_b->bool1`
     - ``int i, int j, mat delta, [Param] B->bool``
   * - :ref:`test_hecke_int_i,int_j,_mat_delta,param_p->bool1`
     - ``int i,int j, mat delta,Param p->bool``
   * - :ref:`test_hecke_int_i,int_j,param_p,ratvec_g->bool1`
     - ``int i,int j,Param p,ratvec g->bool``
   * - :ref:`test_hecke_int_i,int_j,param_p->bool1`
     - ``int i,int j,Param p->bool``


Data Types

.. list-table::
   :widths: 10 20
   :header-rows: 1

   * - Data Type Name
     - Definition
   * - :ref:`KGB_pair1`
     - ``(KGBElt, KGBElt_gen)``
