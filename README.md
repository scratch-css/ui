# Scratch UI
Scratch UI CSS basic components. Inlcudes:

- form
  - field (input)
  - textarea
  - select
  - button
  - radio
  - checkbox
  - toggle slider
  - form groups
- layout 
  - container
  - header
  - footer
- sidebar
  - normal
  - off-canvas
- menu
  - dropdown
  - accordeon 
- modal
  - normal
  - sticky
  
and more coming soon.
    
The default design is just to use it in showcase. It's configurable and API reference is avaiable here.

You can also choose only ones you really need for your project, so you don't have to install them all. For this you can run:

    npm install @scratch-css/ui{/family{/component}}
    
Where `{family}` is the set of similar components (like `form` or `layout`) and `{component}` represents just a component (like `button` or `field` for form, or `header` or `sidebar` for `layout`). They are optional and you don't have to specify.
