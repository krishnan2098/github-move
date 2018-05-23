# How to contribute
I'm really glad you're reading this, because we need volunteer developers to help improve this project.

Bugs? Create an issue and label it as __bug__
New Feature? Create a new issue and label it as __idea__

# Submitting changes
Please create a GitHub Pull Request with a clear list of what you've done . When you send a pull request, remember to attach a screenshot of the changed view along with the issue solved. Make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."

# Coding conventions
Start reading our code and you'll get the hang of it. We optimize for readability:

- Indent usinng four spaces (tabs)
- Avoid logic in views.
- ALWAYS put spaces after list items and method parameters ([1, 2, 3], not [1,2,3]), around operators (x += 1, not x+=1), and around hash arrows.
