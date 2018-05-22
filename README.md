# SandwichClubApp
Android App Project - Udacity
I followed these instructions...
Hey, I was a little lost and this original post helped me out. Heres the steps I took and I hope this helps you guys out that see this.
1.Take a look at the strings.xml there you will find the JSON data you need to use. You will see there that alsoknownas and ingredients use [ ] which means they are arrays.
2. Took a look at the sandwich.java and you’ll see the strings you"ll need to use for JsonUtils.java.
3.Create the strings for JsonUtils.Java and remember that for alsoknownas and ingredients are arrays so u need to create a new array list for each. example (List <String AlsoKnownAs = new ArrayList<>()
4.after you finish the JSON you can open the details.xml and make sure each view has an id so you can refer to it in the details.java.
5. make a reference to each View in the details.java and use the findviewbyid for each view.
6.then way down below you’ll see the populateUI() here you can call the Sandwich.java code.
dont forget to create a reference to the Sandwich.java by just using Sandwich sandwich;
7.To bring the app to life when you click a sandwich you can use something like this in the populateUI() descriptionTextview.setText(sandwich.getDescription()); this should show your sandwich description when you click.

hope this can help you get started in a way.
