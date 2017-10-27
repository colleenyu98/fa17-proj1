# Q0: Why is this error being thrown?

A model and controller for Pokemon was not created yet.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

The pokemon did not have a trainer. The pokemon appeared randomly.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

The line creates a button that says "Throw a Pokeball!" A patch request is also created in routes. The pokemon id is taken in.

# Question 3: What would you name your own Pokemon?

Roccoli, a rock type that is shaped like broccoli because it's hard to bite sometimes. Hard as rock.

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

redirect_to current_trainer. This path needed an id.


# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

This shows puts the full error at the top of the form.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
