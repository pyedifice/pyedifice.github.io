.. Taken from
.. https://github.com/sphinx-doc/sphinx/blob/13da5d7b2fda0da58137534e8fcdb0da9c88e55f/sphinx/ext/autosummary/templates/autosummary/class.rst

edifice.Icon
============

.. currentmodule:: edifice

.. autoclass:: Icon
   :members:                                    <-- add at least this line
   :show-inheritance:                           <-- plus I want to show inheritance...


   
   .. automethod:: __init__

   
   .. rubric:: Methods

   .. autosummary::
      :toctree: stubs
   
      ~Icon.__init__
      ~Icon.did_mount
      ~Icon.did_render
      ~Icon.did_update
      ~Icon.register_props
      ~Icon.register_ref
      ~Icon.render
      ~Icon.render_changes
      ~Icon.set_key
      ~Icon.set_state
      ~Icon.should_update
      ~Icon.will_unmount
   
   

   
   
   .. rubric:: Attributes

   .. autosummary::
   
      ~Icon.children
      ~Icon.props
   
   