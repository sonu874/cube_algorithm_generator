# cube_algorithm_generator
# This is a code written in C++ for the generation of the pattern for scrambling a cube

#define randmax 32767

using namespace;

char pyraminx(int){
	char x;
	array[]={"F","B","R","L","F*","B*","R*","L*","f","r","l","b","f*","b*","l*","r*"};
	for(int i=0;i<l;i++){
		int randnum=rand();
		int randnum=floor((rand()/(float)randmax)*l);
		x=array[randnum];
		cout<<x;
	}
	
}

int main(){
	string s;int l;
	cout<<"Enter the type of cube:";
	cin>>s;
	cout<<"Enter the length";
	cin>>l;
	if(s=="pyraminx"){
		pyraminx(l);
	}
	else if(s=="3x3x3"){
		cube3(l);
	}
	
}
