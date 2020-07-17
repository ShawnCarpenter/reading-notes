# Forms

Forms are our app's eyes and ears, they collect information from the user.

Form data gets sent as name:value pairs like everything else on the internet it's just lists of things.
The input `name="some-name"` attribute provides the name, the value can be set to a default by using the `value="some-value"`

# Styling forms, lists and tables.

There are styling properties that specifically apply to :

- lists: `list-style-type` and `list-style-image`
- tables: `border-spacing` and `border-collapse`


# Events

There's something happening here.

Events are how our app gets told what's happening. To listen for events we need to add an event listener: 
`domElement.addEventListener('event', () => {
    do.stuff
}); `  This says listen for the event `event` and run the callback function when you hear it.

Yet again there is a section for supporting old versions of IE. Not fun.



