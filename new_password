#include<iostream>
#include<string>
using namespace std;
int main(){

    int r;
    cin>>r;
    for(int j=0;j<r;j++){
    int n ;
    string a ;
    cin>>n;
    cin>>a;
    int uc = 0;
    int lc = 0 ;
    int no = 0;
    int sp = 0;
    for(int i = 0 ; i<n ; i++){
        if(a[i] >= 'A' && a[i] <= 'Z'){
            uc++ ;
        }
        if(a[i] >= 'a' && a[i] <= 'z'){
            lc++;
        }
        if(a[i] >= '0' && a[i] <= '9'){
            no++;
        }
        if(a[i] == '@' || a[i] == '#' || a[i] == '*' || a[i] == '&'){
            sp++;
        }

    }
    if(uc == 0){
        a = a +'A';
        n++;
    }
    if(lc == 0){
        a = a + 'a';
        n++;
    }
    if(sp == 0){
        a  = a + '@';
        n++;
    }
    if(no == 0){
        a = a + '1';
        n++;
    }
    if(n<7){
        int dif = 7-n ;
        for(int i = 0 ; i<dif ; i++){
            a += 'D';
        }
    }
    printf("Case #%d: ",j+1);
    cout<<a<<endl;
    }
    return 0;
}
