### How to create an IBDesignable class that draws in Interface Builder ###

1. Create a View .xib file (e.g.: CustomView.xib)

2. Design the user interface in Xcode

3. Set up Auto Layout constraints

4. Create a Swift code file (CustomView.swift)

5. Set .xib file’s “File’s Owner” custom class to CustomView (it must match the class name)

6. Implement both CustomView initializers: init(coder:) and init(frame:)

7. Load the UIView from the .xib file using the NSBundle and UINib classes

8. Add the view as a subview and property for the class (future modifications)

9. Add autoresizing masks for the view to match the size of the CustomView itself

10. Make the view’s frame leverage the design time size of the embedded CustomView’s bounds
