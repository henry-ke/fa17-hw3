## Questions

What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
It fills out the form with a blank. If you were to change it to something like a number, the form would
come filled out.

Go to `localhost:3000/teachers` in your browser; why does this not work?
There is no route to that link.

What type of request did your browser just perform?
It is a get request.

Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
http://localhost:3000/teachers

Why does `localhost:3000/teachers` work now?
It is a post request, so that's the only way to access it without a get.
