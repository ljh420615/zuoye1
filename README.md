package maopao;

public class maopo {

	public static void main(String[] args) {
		int[]p={3,5,2,6,9,7,4,1,8};
		for(int i=0;i<p.length-1;i++){//外循环比对多少趟
			for(int j=0;j<p.length-1-i;j++){//内循环每趟比对多少次
				if(p[j]>p[j+1]){
					int temp=p[j];
							p[j]=p[j+1];
									p[j+1]=temp;
									
				}
			}
		}
		//输出
		for(int i=0;i<p.length;i++){
			System.out.print(p[i]+",");
		}
		System.out.println();
	}
}
