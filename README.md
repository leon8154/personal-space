# personal-space


Find me here!!!

int previousCVal = 0;
int currentCVal = 0;
int previousTVal = 0;
int currentTVal = 0;
int previousPVal = 0;
int currentPVal = 0;
int n;
int x;
int y;
int z;

if(currentCVal>=previousCVal){
	for(x = currentCVal; x>=previousCVal;x--){
		if(currentTVal>=previousTVal){
			for(y=currentTVal;y>=previousTVal;y--);{
				if(currentPVal>=previousPVal){
					for(z=currentPVal;z>=currentPVal;z--){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}
				else{
					for(z=currentPVal;z<=currentPVal;z++){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}			
			
			}
		}
		else{
		for(y=currentTVal;y<=previousTVal;y++);{
				if(currentPVal>=previousPVal){
					for(z=currentPVal;z>=currentPVal;z--){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}
				else{
					for(z=currentPVal;z<=currentPVal;z++){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}			
			
			}
		
		}

	}
}

else{
	for(x = currentCVal; x<=previousCVal;x++){
		if(currentTVal>=previousTVal){
			for(y=currentTVal;y>=previousTVal;y--);{
				if(currentPVal>=previousPVal){
					for(z=currentPVal;z>=currentPVal;z--){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}
				else{
					for(z=currentPVal;z<=currentPVal;z++){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}			
			
			}
		}
		else{
		for(y=currentTVal;y<=previousTVal;y++);{
				if(currentPVal>=previousPVal){
					for(z=currentPVal;z>=currentPVal;z--){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}
				else{
					for(z=currentPVal;z<=currentPVal;z++){
						RightLeg(CNum[n],x,TNum[n],y,PNum[n], z);
					}
				}			
			
			}
		
		}

	}
}
