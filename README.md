# Write-a-simple-program-using-Queue-interface-and-add-6integer-and-remove-2integer-print-using-Queue
import java.util.LinkedList;
import java.util.Queue;

public class QueueInterface {

	public static void main(String[] args)
	{
		Queue<Integer> q
			= new LinkedList<Integer>();

		// Adds elements {0, 1, 2, 3, 4} to
		// the queue
		for (int i = 0; i < 6; i++)
			q.add(i);

		// Display contents of the queue.
		System.out.println("Adding Elements of queue "
						+ q);

		// To remove the element of queue.
		int removedele = q.remove();
		System.out.println("removed element-"
						+ removedele);
		System.out.println(q);
		
		int removedelement = q.remove();
		System.out.println("removed element-"
						+ removedelement);
		System.out.println(q);
	}
}
