.. Taken from
.. https://github.com/sphinx-doc/sphinx/blob/13da5d7b2fda0da58137534e8fcdb0da9c88e55f/sphinx/ext/autosummary/templates/autosummary/class.rst

edifice.Label
=============

.. currentmodule:: edifice

.. autoclass:: Label
   :members:                                    <-- add at least this line
   :show-inheritance:                           <-- plus I want to show inheritance...


   
   .. automethod:: __init__

   
   .. rubric:: Methods

   .. autosummary::
      :toctree: stubs
   
      ~Label.__init__
      ~Label.did_mount
      ~Label.did_render
      ~Label.did_update
      ~Label.register_props
      ~Label.register_ref
      ~Label.render
      ~Label.render_changes
      ~Label.set_key
      ~Label.set_state
      ~Label.should_update
      ~Label.will_unmount
   
   

   
   
   .. rubric:: Attributes

   .. autosummary::
   
      ~Label.children
      ~Label.props
   
   