.. Taken from
.. https://github.com/sphinx-doc/sphinx/blob/13da5d7b2fda0da58137534e8fcdb0da9c88e55f/sphinx/ext/autosummary/templates/autosummary/class.rst

edifice.ScrollView
==================

.. currentmodule:: edifice

.. autoclass:: ScrollView
   :members:                                    <-- add at least this line
   :show-inheritance:                           <-- plus I want to show inheritance...


   
   .. automethod:: __init__

   
   .. rubric:: Methods

   .. autosummary::
      :toctree: stubs
   
      ~ScrollView.__init__
      ~ScrollView.did_mount
      ~ScrollView.did_render
      ~ScrollView.did_update
      ~ScrollView.register_props
      ~ScrollView.register_ref
      ~ScrollView.render
      ~ScrollView.render_changes
      ~ScrollView.set_key
      ~ScrollView.set_state
      ~ScrollView.should_update
      ~ScrollView.will_unmount
   
   

   
   
   .. rubric:: Attributes

   .. autosummary::
   
      ~ScrollView.children
      ~ScrollView.props
   
   