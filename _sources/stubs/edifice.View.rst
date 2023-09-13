.. Taken from
.. https://github.com/sphinx-doc/sphinx/blob/13da5d7b2fda0da58137534e8fcdb0da9c88e55f/sphinx/ext/autosummary/templates/autosummary/class.rst

edifice.View
============

.. currentmodule:: edifice

.. autoclass:: View
   :members:                                    <-- add at least this line
   :show-inheritance:                           <-- plus I want to show inheritance...


   
   .. automethod:: __init__

   
   .. rubric:: Methods

   .. autosummary::
      :toctree: stubs
   
      ~View.__init__
      ~View.did_mount
      ~View.did_render
      ~View.did_update
      ~View.register_props
      ~View.register_ref
      ~View.render
      ~View.render_changes
      ~View.set_key
      ~View.set_state
      ~View.should_update
      ~View.will_unmount
   
   

   
   
   .. rubric:: Attributes

   .. autosummary::
   
      ~View.children
      ~View.props
   
   