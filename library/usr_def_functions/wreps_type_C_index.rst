.. _wreps_type_C.at_index:

wreps_type_C.at Function Index
=======================================================
|



Functions

.. list-table::
   :widths: 10 20
   :header-rows: 1

   * - Function
     - Argument(s) -> Results
   * - :ref:`normalize_[int]_v->[int]2`
     - ``[int] v->[int]``
   * - :ref:`expand_[int]_v,_int_r->[int]2`
     - ``[int] v, int r->[int]``
   * - :ref:`normalize_symbol_s->symbol2`
     - ``Symbol S->Symbol``
   * - :ref:`rank_[int]_f->int2`
     - ``[int] f->int``
   * - :ref:`rank_symbol_s->int2`
     - ``Symbol S->int``
   * - :ref:`symbol_orbit_p->symbol1`
     - ``Orbit P->Symbol``
   * - :ref:`wrep_symbol_s->wrep2`
     - ``Symbol S->Wrep``
   * - :ref:`wrep_orbit_p->wrep2`
     - ``Orbit P->Wrep``
   * - :ref:`orbit_symbol_s->orbit1`
     - ``Symbol S->Orbit``
   * - :ref:`symbol_wrep_sigma->symbol2`
     - ``Wrep sigma->Symbol``
   * - :ref:`orbit_wrep_sigma->orbit1`
     - ``Wrep sigma->Orbit``
   * - :ref:`\=_Wrep__a,Wrep_b->bool2`
     - ``Wrep  a,Wrep b->bool``
   * - :ref:`symbols_equal_symbol_a,symbol_b->bool2`
     - ``Symbol a,Symbol b->bool``
   * - :ref:`dimension_wrep_sigma->int2`
     - ``Wrep sigma->int``
   * - :ref:`is_special_symbol_s->bool1`
     - ``Symbol S->bool``
   * - :ref:`is_special_orbit_p->bool1`
     - ``Orbit P->bool``
   * - :ref:`is_special_wrep_sigma->bool1`
     - ``Wrep sigma->bool``
   * - :ref:`special_star_symbol_s->string1`
     - ``Symbol S->string``
   * - :ref:`special_star_orbit_p->string1`
     - ``Orbit P->string``
   * - :ref:`special_star_wrep_sigma->string1`
     - ``Wrep sigma->string``
   * - :ref:`symbols_rootdatum_rd->[symbol]2`
     - ``RootDatum rd->[Symbol]``
   * - :ref:`wreps_rootdatum_rd->[wrep]2`
     - ``RootDatum rd->[Wrep]``
   * - :ref:`cut_off_string_[int]_v)=(int,[int]->last(#v,_(int_i)bool1`
     - ``[int] v)=(int,[int]->last(#v, (int i)bool``
   * - :ref:`cut_off_last_string_[int]_v->(int,[int])3`
     - ``[int] v->(int,[int])``
   * - :ref:`extract_strings_[int]_v->[int]3`
     - ``[int] v->[int]``
   * - :ref:`a_levi_factor_int_rank,_[int]_tau->[int]3`
     - ``int rank, [int] tau->[int]``
   * - :ref:`ac_levi_factor_int_rank,_[int]_tau->(int,[int])3`
     - ``int rank, [int] tau->(int,[int])``
   * - :ref:`is_max_[[int]]_taus,[int]_tau->bool3`
     - ``[[int]] taus,[int] tau->bool``
   * - :ref:`max_only_[[int]]_taus->[[int]]3`
     - ``[[int]] taus->[[int]]``
   * - :ref:`levi_signature_int_rank,[[int]]_tau_invariants->([[int]],[(int,[int])])3`
     - ``int rank,[[int]] tau_invariants->([[int]],[(int,[int])])``
   * - :ref:`max_first_entry_[[int]]_v->int3`
     - ``[[int]] v->int``
   * - :ref:`keep_by_first_entry_[[int]]_v,int_k->[[int]]3`
     - ``[[int]] v,int k->[[int]]``
   * - :ref:`keep_by_first_entry_and_truncate_[[int]]_v,int_k->[[int]]3`
     - ``[[int]] v,int k->[[int]]``
   * - :ref:`max_tagged_entry_[(int,[int])]_v->int3`
     - ``[(int,[int])] v->int``
   * - :ref:`keep_by_first_entry_[(int,[int])]_v,int_k->[(int,[int])]4`
     - ``[(int,[int])] v,int k->[(int,[int])]``
   * - :ref:`keep_by_first_entry_and_truncate_[(int,[int])]_v,int_k->[(int,[int])]3`
     - ``[(int,[int])] v,int k->[(int,[int])]``
   * - :ref:`wrep_int_rank,[[int]]_tau_invariants->wrep3`
     - ``int rank,[[int]] tau_invariants->Wrep``
   * - :ref:`wrep_block_b,[int]_cell->wrep3`
     - ``Block B,[int] cell->Wrep``
   * - :ref:`wreps_block_b,[[int]]_cells->[wrep]3`
     - ``Block B,[[int]] cells->[Wrep]``
   * - :ref:`print_wreps_cpt_block_b,[[int]]_cells->void2`
     - ``Block B,[[int]] cells->void``
   * - :ref:`print_wreps_block_b,[[int]]_cells->void2`
     - ``Block B,[[int]] cells->void``


Data Types

.. list-table::
   :widths: 10 20
   :header-rows: 1

   * - Data Type Name
     - Definition
   * - :ref:`Orbit3`
     - ``[int]``
   * - :ref:`Symbol3`
     - ``[[int]]``
   * - :ref:`Wrep3`
     - ``([int],[int])``
