# Algorith Analysis

### Common arithmetic mistakes

- INT overflow :

Sum three numbers.
Constraints: 0 < a,b,c < 10^9

	int main(){
	  int a , b,c;
	  scanf(“%d %d %d”,&a,&b,&c);
	  int ans = a + b + c;
	  printf(“%d”,ans);
	  return 0;
	}

This program won't give correct output for all cases as 3*10^9 cannot be stored in INTS you need long long int or unsigned int (4*10^9). what if 0


- Comparing Doubles:

float/double don’t have infinite precision. BEWARE ( 6/15 digit precision for them respectively)

	int main(){
	  float a ;
	  scanf(“%f”,&a);
	  if(a == 10 ) printf(“YES”);
	  return 0;
	}


- Negative Modulo:

Example 

	int main(){
	 int a = (10 - 12) % 5;
	 if(a == -2) printf(“YES”);
	 return 0;
	}

[modula arithmatic explained] [https://brilliant.org/wiki/modular-arithmetic/]

