# CISC275-Fall2018-first-git
1. Create java files to make this code compile and run.

2. What five objects are created in the main?
First, we create an arrayList named dogs, then we create 3 Dog objects, and 
add them into "dogs", in the end, we create an Comparator object.
3. Can you spot the comparator constructor call? Where is the class definition for the comparator?
new Comparator<Animal>, this is the constructor call
@Override
	public int compare(Animal a, Animal b){
	    return a.getLegs() - b.getLegs();
	}
this is the definition of the class
