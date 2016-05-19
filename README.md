# kulkeez.github.io
Namaste!
===================

Halo! I'm all charged up - this is my first Markdown document and I am using the **[StackEdit](https://stackedit.io/editor)** in-browser mark down editor. 

----------

Genesis
-------------

It all started on a Tuesday evening when I was trying to digest a 150 page Design document. The kids were raising a ruckus and I was desperate to cool them down. "How about me writing a game that quizzes you multiplication tables ?", I challenged the boys. Both were enthusiastic and took the bait easily. The next hour was spent quickly coding the *MultiplicationQuizzer*.


```
/**
 * 
 * A quiz program to reinforce multiplication tables. I got bored 
 * asking random multiplication questions and delegated it to this program.
 * 
 * @author Vikram Kulkarni
 *
 */
public class MultiplicationQuizzer {

....
....
	private static int getRandomNumberInRange(int min, int max) {
		if (min >= max) {
			throw new IllegalArgumentException("max must be greater than min");
		}

		Random rand = new Random();
		return rand.nextInt((max - min) + 1) + min;
	}
	
	private static int getRandomNumberFromShuffleList() {
		long seed = System.nanoTime();
		Integer randInteger = null;
		if(!integerList.isEmpty()) {
			randInteger = integerList.get(0);
			integerList.remove(0);
		}
		return randInteger;
	}
....
....
}
```


More thought to follow, stay tuned ...

