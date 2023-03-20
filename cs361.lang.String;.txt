import java.lang.String;
import java.util.Arrays;
import java.util.List;
import java.util.stream.*;
import java.util.*;
import java.nio.file.*;
import java.io.IOException;


	

public class Streams {
	public static void main(String[] args) throws IOException {
		// 1. Integer Stream
		//IntStream
			//.range(1, 10)
			//.forEach(System.out::print);
		//System.out.println();
		
		//IntStream
		//.range(1, 10)
		//.skip(5)
		//.forEach(x -> System.out.println(x));
//	System.out.println();
		
		//6. average of squares of an int array
			Arrays.stream(new int[] {2, 4, 6, 8, 10})
				.map(x -> x * x)
				.average()
				.ifPresent(System.out::println);
	}
}


// 2. Integer Stream with skip
//IntStream
	//.range(1, 10)
	//.skip(5)
	//.forEach(x -> System.out.println(x));
//System.out.println();

// 3. Integer Stream with sum
//System.out.println(
//IntStream
//	.range(1, 5)
//	.sum());
//System.out.println()
//}


//6. average of squares of an int array
	//	Arrays.stream(new int[] {2, 4, 6, 8, 10})
		//	.map(x -> x * x)
			//.average()
			//.ifPresent(System.out::println);