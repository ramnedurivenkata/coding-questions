#include <stdio.h>

int main() {
	int testcsno;
	scanf("%d",&testcsno);
	for(int t=1;t<=testcsno;t++){
	    
	    int arraysize,S;
	    scanf("%d %d",&arraysize,&S);
	    int array[arraysize];
	    for(int temp=0;temp<arraysize;temp++)
	    {
	        scanf("%d",&array[temp]);
	    }
	    int firstindex,lastindex,sum=array[0];
	    firstindex=0;
	    int temp;
	    for(temp=1;temp<arraysize;temp++)
	    {
            while(sum>S){
                sum=sum-array[firstindex];
                firstindex+=1;
            }
            
	        if(sum==S){
	            printf("%d %d\n",firstindex+1,temp);
	            break;
	        }
            
            sum+=array[temp];

	    }
	    if(temp==arraysize){
	        printf("-1\n");
	    }
	}
}
