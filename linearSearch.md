public class linearsearch{
  public static void main(String[] args){
int [] even={2,4,6,8,10,12,14,16,18,20};
    int target = 2;
    int result =linearSearch(even,target);
    System.out.println("target " +  target  + "is on the index "+ result);
  }
  public static int linearSearch(int[]array,int target){
    for(int i=0;i<array.length;i++){
      if (array[i]==target){
        return i;
      }
    }
    return -1;
    
  }
}
