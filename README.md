# Boi-vui
test bai
    Lop: 58PM    Email: luongtd62@wru.vn    Project: Boi vui */  #include<iostream> #include<conio.h> #define N 2017 using namespace std; // Ham tinh Can - chi void Canchi( int n){ 	int can,chi; 	int temp; // gan gia tri cho temp de tinh tong => Menh = temp + temp2 	int temp1; 	can = n % 10; 	chi = n % 12; 	switch (can){ 		case 0: 		cout<<"Canh  " ; 		temp = 4 ; 		break; 		case 1: 		cout<<"Tan  " ; 		temp = 4; 		break;	 		case 2: 		cout<<" Nham " ; 		temp = 5; 		break; 		case 3: 		cout<<"Qui  " ; 		temp =5 ; 		break; 		case 4: 		cout<<"Giap  " ; 		temp=1; 		break; 		case 5: 		cout<<"At  " ; 		temp =1; 		break; 		case 6: 		cout<<"Binh  " ; 		temp =2; 		break; 		case 7: 		cout<<"Dinh  " ; 		temp = 2; 		break; 		case 8: 		cout<<"Mau  " ; 		temp =3; 		break; 		case 9: 		cout<<"Ki  " ; 		temp =3; 		break; 	} 	// cach tinh Chi; 	switch(chi){ 		case 0: 		cout<<"Than "; 		temp1 = 1; 		break; 		case 1: 		cout<<"Dau "; 		temp1 = 1; 		break; 		case 2: 		cout<<"Tuat "; 		temp1 = 2 ; 		break; 		case 3: 		cout<<"Hoi"; 		temp1 = 2; 		break; 		case 4: 		cout<<"Ty ";// ty 		temp1 = 0; 		break; 		case 5: 		cout<<"Suu "; 		temp1 = 0; 		break; 		case 6: 		cout<<"Dan "; 		temp1 = 1 ; 		break; 		case 7: 		cout<<"Mao "; 		temp1 = 1 ; 		break; 		case 8: 		cout<<"Thin "; 		temp1 = 2 ; 		break; 		case 9: 		cout<<"Ti"; 		temp1 = 2 ; 		break; 		case 10: 		cout<<"Ngo "; 		temp1 = 0; 		break; 		case 11: 		cout<<"Mui"; 		temp1 = 0; 		break;	 		 } 	cout<<endl; 	cout<<"Ban la nguoi: "; 	int Menh ; 	Menh = temp + temp1 ; 	switch(Menh){ 	 case 1:  	   cout<<"Menh Kim"<< endl; 	   break ;    case 2:  	   cout<<"Menh Thuy"<< endl; 	   break ;    case 3:  	   cout<<"Menh Hoa"<< endl; 	   break ;    case 4:  	   cout<<"Menh Tho"<< endl; 	   break ;    case 5:  	   cout<<"Menh Moc"<< endl; 	   break ; 	}  	///////////////////////////////////////////////////////////////// 	if(Menh > 5) 	{ 		Menh= Menh - 5 ; 		switch(Menh){    case 1:  	   cout<<"Menh Kim"<< endl; 	   break ;    case 2:  	   cout<<"Menh Thuy"<< endl; 	   break ;    case 3:  	   cout<<"Menh Hoa"<< endl; 	   break ;    case 4:  	   cout<<"Menh Tho"<< endl; 	   break ;    case 5:  	   cout<<"Menh Moc"<< endl; 	   break ; 	        } 	} 	cout<<endl; 	 		switch (Menh) 		{ 		case 1 :  			cout<<"Duoi day la nhung dieu co ban nhat doi voi nguoi mang menh Kim: " <<endl; 			cout<<"Mau Sac : " << endl<<"   Hop mau: Vang, Nau Dat...: "<<endl<<"  Xung khac mau: Do, Hong, Tim"<<endl; 			cout<<"Cong viec phu hop: Lien quan den Vang Bac, khai thac mo , Lap rap xe hoi..."<<endl; 			cout<<"Tinh Duyen:"<<endl<<"  Kim la do Dat sinh ra vang bac nen menh Kim hop voi menh Tho"<<endl<<"  Hop voi nguoi cung menh Kim hoac nguoi mang menh Moc"<<endl; 			cout<<"Vat phong thuy: Da thach anh mau nau"<<endl; 			cout<<"Nen chon xe hoi mau Trang de hop voi ban Menh"; 			break ; 		case 2 :  			cout<<"Duoi day la nhung dieu co ban nhat doi voi nguoi mang menh Thuy: " <<endl; 			cout<<"Mau Sac : " << endl<<"  Hop mau: Xanh, Den,Trang...: "<<endl<<"  Xung khac mau: Vang, Nau dat"<<endl; 			cout<<"Cong viec phu hop: Lien quan den cac cong viec ve KInh Doanh, Tai Chinh, Ngan Hang.."<<endl; 			cout<<"Tinh Duye"<<endl<<":  Hop voi nhung nguoi mang menh Kim vi Kim nung chay sinh ra nuoc"<<endl<<"  Xung khac voi nguoi mang menh Tho vi dat luon ngan can nuoc.."<<endl; 			break ; 		case 3 :  			cout<<"Duoi day la nhung dieu co ban nhat doi voi nguoi mang menh Hoa: " <<endl; 			cout<<"Mau Sac : " << endl<<"   Hop mau: Do, Cam, Hong, Tim, Xanh la Cay.. "<<endl<<"   Xung khac mau: Den, Xanh nuoc"<<endl; 			cout<<"Cong viec phu hop: Cac nghanh hop voi hanh Hoa va hanh Moc nhu: Tho Anh, Nau an, Hoa trang, Nung Gach "<<endl; 			cout<<"Tinh Duyen:"<<endl<<"  Hop voi nguoi menh Moc va menh Hoa "<<endl<<"  Ky voi  menh Thuy nhung  doi khi se phai can den nguoi co menh Thuy "<<endl; 			cout<<"Vat phong thuy: Da Thach Anh,Da Mat Ho Xanh"<<endl; 			cout<<"Nen chon xem hoi mau Xanh la  cay"; 			break ; 		case 4 :  			cout<<"Duoi day la nhung dieu co ban nhat doi voi nguoi mang menh Tho: " <<endl; 			cout<<"Mau Sac : " << endl<<"  Hop mau: Vang, Nau Dat...: "<<endl<<"  Xung khac mau: Do, Hong, Tim"<<endl; 			cout<<"Cong viec phu hop: Kinh doanh Bat dong san, Dia oc, Cac cong tring dan dung..."<<endl; 			cout<<"Tinh Duyen:"<<endl<<"  XUng khac voi nguoi menh Thuy"<<endl<<"  Hop voi nguoi mang menh Moc"<<endl; 			break ; 		case 5 :  			cout<<"Duoi day la nhung dieu co ban nhat doi voi nguoi mang menh Moc: " <<endl; 			cout<<"Mau Sac : " << endl<<"Nau va Xanh la cay "<<endl<<"Xung khac mau: Trang, Xam ,Ghi"<<endl; 			cout<<"Cong viec phu hop: Ho voi nhung nganh nghe buon ban, thu lai loi nhan nhanh nhu, mo Quan An, khi dot, xang dau, my pham.."<<endl; 			cout<<"Tinh Duyen:"<<endl<<" Hop voi nguoi menh Thuy, Hoa "<<endl<<"2.Hya xung khac voi menh KIm, menh Tho,va doi khi la nguoi menh Moc"<<endl; 			break ;  		}  } //  Ham tinh cung hoang dao void Cunghoangdao( int ngay, int thang) { 	switch(thang) 	{ 	case 1: 		if( ngay >=20 && ngay<=31) 		{ 			cout<<"Cung Hoang dao cua ban la: Bao Binh"<<endl; 		} 		if(ngay>=1&&ngay <=19) 		{ 			cout<<"Cung Hoang dao cua ban la: Ma Ket"<<endl; 		} 		break; 	case 2: 		if(ngay >=1&& ngay <=18) 		{ 			cout<<"Cung Hoang dao cua ban la: Bao Binh"<<endl; 		} 		if(ngay>=19&&ngay<=29) 		{ 			cout<<"Cung Hoang dao cua ban la: Song Ngu"<<endl; 		} 		break; 	case 3: 		if(ngay>=1&&ngay<=20) 		{ 			cout<<"Cung Hoang dao cua ban la: Song Ngu"<<endl; 		} 		if(ngay>=21&&ngay<31) 		{ 			cout<<"Cung Hoang dao cua ban la: Bach Duong"<<endl; 		} 		break; 	case 4: 		if(ngay>=1&&ngay<=19) 		{ 			cout<<"Cung Hoang dao cua ban la: Bach Duong"<<endl; 		} 		if(ngay>=20&&ngay<=30) 		{ 			cout<<"Cung Hoang dao cua ban la: Kim Nguu"<<endl; 		} 		break; 	case 5: 		if(ngay>=1&&ngay<=20) 		{ 			cout<<"Cung Hoang dao cua ban la: Kim Nguu"<<endl; 		} 		if(ngay>=20&&ngay<=30) 		{ 			cout<<"Cung Hoang dao cua ban la: Kim Nguu"<<endl; 		} 		break;    case 6: 		if(ngay>=1&&ngay<=21) 		{ 			cout<<"Cung Hoang dao cua ban la: Song Tu"<<endl; 		} 		if(ngay>=22&&ngay<=30) 		{ 			cout<<"Cung Hoang dao cua ban la:Cu Giai "<<endl; 		} 		break;   case 7: 		if(ngay>=1&&ngay<=22) 		{ 			cout<<"Cung Hoang dao cua ban la: Cu Giai"<<endl; 		} 		if(ngay>=23&&ngay<=31) 		{ 			cout<<"Cung Hoang dao cua ban la: Su Tu"<<endl; 		} 		break;   case 8: 		if(ngay>=1&&ngay<=22) 		{ 			cout<<"Cung Hoang dao cua ban la: Su Tu"<<endl; 		} 		if(ngay>=23&&ngay<=31) 		{ 			cout<<"Cung Hoang dao cua ban la: Xu Nu"<<endl; 		} 		break;    case 9: 		if(ngay>=1&&ngay<=22) 		{ 			cout<<"Cung Hoang dao cua ban la: Xu Nu"<<endl; 		} 		if(ngay>=23&&ngay<=30) 		{ 			cout<<"Cung Hoang dao cua ban la: Thien Binh"<<endl; 		} 		break;    case 10: 		if(ngay>=1&&ngay<=23) 		{ 			cout<<"Cung Hoang dao cua ban la: Thien Binh"<<endl; 		} 		if(ngay>=24&&ngay<=31) 		{ 			cout<<"Cung Hoang dao cua ban la: Ho Cap"<<endl; 		} 		break;    case 11: 		if(ngay>=1&&ngay<=21) 		{ 			cout<<"Cung Hoang dao cua ban la: Ho Cap"<<endl; 		} 		if(ngay>=22&&ngay<=30) 		{ 			cout<<"Cung Hoang dao cua ban la: Nhan Ma"<<endl; 		} 		break;    case 12: 		if(ngay>=1&&ngay<=21) 		{ 			cout<<"Cung Hoang dao cua ban la: Nhan Ma"<<endl; 		} 		if(ngay>=22&&ngay<=31) 		{ 			cout<<"Cung Hoang dao cua ban la: Ma Ket"<<endl; 		} 		break; 	} } //// Ham tinh nam nhuannnn void Namnhuan(int year, int ngay)
{
 if( (year%400==0) || (year%4==0 && year%100!=0))
 {
	 if( ngay >29)
	 {
		 cout<<"So ngay ban nhap khong dung xin moi nhap lai!";
	 }
 }

}

 /*void namnhuan(int nam, ) { 	bool kiemtranam; 	if ((nam%4==0 && nam%100!=0)||(nam%400==0)) 		kiemtranam=true; 	else kiemtranam=false; 	if (kiemtranam==true) 	{ 		if (nam<1 || nam>29) 			{ 				cout<<"Ngay - thang - nam sinh sai !!!"; 			} 	} 	else 	{ 		if (nam<1 || nam>28) 			{ 				cout<<"Ngay - thang - nam sinh sai !!!"; 			} 	} }*/ // Ham tinh tuoi void Tinhtuoi( int nam) { 	int Tuoi; 	Tuoi = N - nam ; 	cout<<"Tuoi cua ban la: "<<Tuoi<<endl; } int main() { 	int a,b ;// nhap su lua chon 	int ngay, thang, nam;     do{ 		cout<<"Xin moi nhap Ngay - Thang - Nam sinh cua ban!!! "<<endl; 		cout<<"Ban sinh ngay: "; cin >> ngay; 		cout<<"Ban sinh thang: ";cin>> thang; 		cout<<"Ban sinh nam: ";cin>>nam;	 		//  THAU CO THE XEM CHO EM DOAN NAY SAI O DAU DUOC KHONG A! 		/////////////////////////////////////////////////////////////////////////// 		// kiem tra nam nhuan 		/*if(thang ==4 || thang == 6 || thang==9||thang==11 && ngay >30) 			cout<<"So ngay ban nhap khong dung!"; 		if(thang ==1||thang==3||thang==5||thang==7|| thang ==8|| thang== 10|| thang==12 && ngay> 31) 			cout<<"So ngay ban nhap khong dung "; 		if(thang ==2 && ngay > 29) 			cout<<"So ngay ban nhap khong dung "; 			//cout<<"Ngay hoac Thang cua ban nhap khong dung xin moi ban nhap lai! "; 		}while(thang == 4|| thang==9 || thang ==11 ||thang ==6||thang ==1|| thang==3 || thang ==5|| thang ==7|| thang ==8 || thang ==10 || thang== 12  && ngay > 31 && ngay >30 && ngay > 29);*/ 		if( ngay >32|| thang>12 || ngay <=0 || thang <=0 ) 			// EM VIET TAM DE CHAY DOAN CODE SAU///////////////////// 			cout<<"Ngay hoac Thang cua ban nhap khong dung xin moi ban nhap lai! "; 		}while( ngay >32|| thang>12 || ngay <=0 || thang <=0); 		//namnhuan(nam); 		cout <<"========================================================================" <<endl; 		Tinhtuoi( nam) ; 	    Cunghoangdao(ngay,thang);	      	Canchi(nam); 			  	getch(); 	return 0; }
