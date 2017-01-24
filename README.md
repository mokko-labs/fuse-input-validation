# fuse-input-validation
Would like to create reusable and highly functional input validation methods in Fuse components.

## ValidatedTextInput
ValidatedTextInput is a TextInput with appropriate properties and states to indicate the validity of input.

### IsValid (bool)
This property indicates if the text input is valid.

### Required (bool)
This property is used to control whether input is required in order to be valid.

### IsUntouched (bool)
This property indicates whether the user has entered enything into this control.

### MinLength (number)
This property is used to control how long the text input must be before it becomes valid. Default value is 1.
