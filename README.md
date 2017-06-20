public class BubbleSort
{
    public void sort(int[] a)
    {
        int temp = 0;//空瓶
        for (int i = a.length - 1; i > 0; --i)
      //多少伦
     {
            for (int j = 0; j < i; ++j)
           //多少次
            
            {
                if (a[j + 1] < a[j])
                {
                    temp = a[j];
                    a[j] = a[j + 1];
                    a[j + 1] = temp;
                }
            }
        }
    }
}
