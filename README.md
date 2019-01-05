# mengetahui-kuadran-suatu-koordinat

    #include<iostream>
    #include<stdio.h>
    #include<conio.h>
    using namespace std;
    int main()
    {
        int x,y;
        cout << "\t\t ================== \n";
        cout << "\t\t Program koordinat \n";
        cout << "\t\t ================== \n";
        cout << "\t\t Masukkan nilai x :";cin>>x;
        cout << "\t\t Masukkan nilai y :";cin>>y;

        if(x>0&&y>0)
            printf("\t\t KUADRAN 1");
        if(x>0&&y<0)
            printf("\t\t KUADRAN 2");
        if(x<0&&y<0)
            printf("\t\t KUADRAN 3");
        if(x<0&&y>0)
            printf("\t\t KUADRAN 4");
        if(x==0&&y==0)
            printf("\t\t TITIK PUSAT");
        getch ();
    }
    
    
 hasil
 ![img](https://github.com/septianaana/mengetahui-kuadran-suatu-koordinat/blob/master/kuadran%20suatu%20koordinat.png?raw=true)
