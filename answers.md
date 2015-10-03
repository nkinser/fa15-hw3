1. What is the difference between new and create for a model?
The difference is that with new you have to call new on the model (model = name_of_model.new), then set the columns to what you want (model.column_name = column_value), and then save the model (model.save). Create does all of the above in one step with the syntax (model = name_of_model.create column_name:column_value).

2. What command combined with new will emulate the same behavior as create?
Save

3. What is the column that exists on every table but we did NOT define?
Timestamps

4. What single line of ruby code can insert a cat with the name "hat" in the database?
hat = Cat.create name: "hat"

5. What was the most confusing part over the last few weeks?
The most confusing part is learning the ruby and html syntax and then also having to sometimes combine them. Also keeping track of how everything is connected and knowing which folders contain which files is also difficult for me.

6. How did you like this homework in comparison with the others?
I liked this homework. I thought it was cool how it brought together a lot of the stuff we've learned so far.
