- Create a View .xib file (e.g.: CustomView.xib)

- Design the user interface in Xcode

- Set up Auto Layout constraints

- Create a Swift code file (CustomView.swift)

- Set .xib file’s “File’s Owner” custom class to CustomView (it must match the class name)

- Implement both CustomView initializers: init(coder:) and init(frame:)

- Load the UIView from the .xib file using the NSBundle and UINib classes

- Add the view as a subview and property for the class (future modifications)

- Add autoresizing masks for the view to match the size of the CustomView itself

- Make the view’s frame leverage the design time size of the embedded CustomView’s bounds
