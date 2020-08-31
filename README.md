# In-memory-reverse-array-easy

```C#
  static int[] ReverseArrayInMemory(int [] arr)
        {
            for(int i=0; i<arr.Length /2; i++)
            {
                int temp = arr[i];
                arr[i] = arr[arr.Length - i - 1];
                arr[arr.Length - i - 1] = temp;
            }

            return arr;
        }
````
