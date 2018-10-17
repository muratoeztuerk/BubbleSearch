public class BubbleTest {

	public static void main(String[] args) {
		int[] array = { 32, 35, 62, 762, 82, 1, 76, 94, 43 };
		BubbleTest bubbleTest = new BubbleTest();
		System.out.println(bubbleTest.arrayToString(bubbleTest.bubbleSort(array)));
		System.out.println(bubbleTest.arrayToString(bubbleTest.bubbleSortReverse(array)));

	}

	String arrayToString(int[] array) {
		String string = "[";
		for (int i = 0; i < array.length; i++) {
			string += array[i];
			if (i < array.length - 1)
				string += ",";
		}
		return string += "]";
	}

	int[] bubbleSort(int[] array) {
		int temp;
		for (int i = 0; i < array.length; i++) {
			for (int j = 0; j < array.length; j++) {
				if (array[i] < array[j] && i > j) {
					temp = array[i];
					array[i] = array[j];
					array[j] = temp;
				}
			}
		}

		return array;
	}

	int[] bubbleSortReverse(int[] array) {
		int temp;
		for (int i = 0; i < array.length; i++) {
			for (int j = 0; j < array.length; j++) {
				if (array[i] < array[j] && i < j) {
					temp = array[i];
					array[i] = array[j];
					array[j] = temp;
				}
			}
		}

		return array;
	}

}
