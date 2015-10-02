1. What is the difference between new and create for a model?
'New' instantiates but doesn't actually save it until 'save' is called. 'Create' does both.
2. What command combined with new will emulate the same behavior as create?
.save
3. What is the column that exists on every table but we did NOT define?
id
4. What single line of ruby code can insert a cat with the name "hat" in the database?
c = Cat.create :name => "hat"
5. What was the most confusing part over the last few weeks?
Ruby on Rails has a lot of intricacies that makes it tough to initially find out, like routing and where things are located and what things to change, but once I get the hang of it I feel like everything will be super simple to do.
6. How did you like this homework in comparison with the others?
Instead of feeling like a homework with separate problems, this one had questions which all built off of each other and eventually culminated in an end product, which gives a sense of acclompishment. 