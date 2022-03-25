# Codeforcescpp-445A
#include <bits/stdc++.h>
using namespace std;

int main() {
	int n,m;
  cin >> n >> m;
  char c[101][101];
  for(int i=0;i<n;i++){
    for(int j=0;j<m;j++){
      cin >> c[i][j];
      if(c[i][j]=='_'){
        cout << "_";
      }
      else if((i+j)%2==0){
        cout << "B";
      }
      else{
        cout << "W";
      }
    }
    cout << endl;
  }
  
	return 0;
}
