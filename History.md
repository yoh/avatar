### 0.7.15

- **IMPORTANT:** There is now an `Avatar.setOptions()` method which must be used to override the default options (rather than just assigning to `Avatar.options` directly).
- Provided an option to override the default Avatar sizes and to create new ones.
- The CSS is now generated on the server based on the current options, so it's no longer necessary to provide your own CSS if you've customised the CSS prefix using the option that was introduced in version 0.7.13.


### 0.7.14

- Updated repo URL.

### 0.7.13

- Added custom CSS prefix option (thanks @raiyankamal!)

### 0.7.12

- Cleaned up getServices (thanks @gwendall!)
- Only remove 'display' if url changes (thanks @rodrigok!)

### 0.7.11

- Added LinkedIn support (thanks @raiyankamal!)

### 0.7.10

### 0.7.9

- Adding `customImageProperty` option for storing avatars on a custom user property.
- Refactored `getServices`.
- Started using `getDescendantProp` instead of assuming properties are stored on the `user.profile` object. 
- Added roadmap.
- Changed package name to `utilities:avatar`. 
- Changed logo to the only “Avatar” that matters. 