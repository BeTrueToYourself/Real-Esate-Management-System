# Real-Esate-Management-System
 Maintain a detailed record of anyone and anything that passes through your building. Let residents register guests, set special permissions, and receive real time updates on pickups and deliveries.  BuildingLink's hardware integrations allow you to scan incoming packages and collect signatures, and the patented KeyLink system lets you share apartment keys with safety and ease. 
//Name:- Ashwani Kumar
//Roll No.:- RK18PGB41
//Section:- K18PG
//Subject:- CSE201 (Object Oriented Programming)
//Faculty Name:- Nahita Pathania
#include<iostream> 
#include<conio.h> 
using namespace std;
#include<fstream>
#include<string.h>
#include<process.h> 
class cst
{ 
	  public: 
	  	int p; 
	void get();
	    };
void cst::get() 
          { 
             cout<<"==============================================================================================================================="<<endl;
//            int p;
              cout<<"The various Customer Module are as follows:- "<<endl;
              cout<<"1.) Land Accomodation"<<endl;
              cout<<"2.) Home Accomodation" <<endl;  
              cout<<"3.) Rented Flat Accomodation"<<endl;
              cout<<"0.) Exit"<<endl;
              cout<<"==============================================================================================================================="<<endl;
              cout<<"Press 1 for Land Accomodation "<<endl;
              cout<<"Press 2 for Home Accomodation "<<endl;
              cout<<"Press 3 for Rented Flat Accomodation "<<endl;
              cout<<"Press 0 to Exit"<<endl;
              cout<<"==============================================================================================================================="<<endl;
              cout<<"Enter what you want from the Above Given Module:- "<<endl;
              cin>>p;
              if(p==1)
              {
              	cout<<"Land Accomodation"<<endl;
			  }
			  else if(p==2)
			  {
			  	cout<<"Home Accomodation"<<endl;
			  }
			  else if(p==3)
			  {
			    cout<<"Rented Flat Accomodation"<<endl;
			  }
			  else if (p == 0)
			  {
					exit(-2);
			  }
			  cout<<"==============================================================================================================================="<<endl;
			  int x;
			  cout<<"The Various locations are as follows:- "<<endl;      
              cout<<"1.) Jalandhar"<<endl;
              cout<<"2.) Phagwara" <<endl;  
              cout<<"3.) Amritsar"<<endl;
              cout<<"4.) Ludhiana"<<endl;
              cout<<"5.) Hoshiar Pur"<<endl;
              cout<<"==============================================================================================================================="<<endl;
              cout<<"Press 1 for Jalandhar "<<endl;
              cout<<"Press 2 for Phagwara"<<endl;
              cout<<"Press 3 for Amritsar"<<endl;
              cout<<"Press 4 for Ludhiana"<<endl;
              cout<<"Press 5 for Hoshiar Pur"<<endl;
              cout<<"==============================================================================================================================="<<endl;
              cout<<"Enter  the location Where you want:- "<<endl;
              cin>>x;
               switch(x)
              {
			  
              case 1:
              {
              	cout<<"Jalandhar"<<endl;
              	break;
			  }
			   case 2:
			  {
			  	cout<<"Phagwara"<<endl;
			  		break;
			  }
		 case 3:
			 {
			  	cout<<"Amritsar"<<endl;
			  		break;
			 }
			 default :
			 	{
			 		cout<<"Invalid Input"<<endl;
			 		break;
				 }
		  case 4:
		     {
			  	cout<<"Ludhiana"<<endl;
			  		break;
			 }
		 case 5:
			{
			  	cout<<"Hoshiar Pur"<<endl;
			  		break;
			}
		}
	
			cout<<"==============================================================================================================================="<<endl;
			int q;
			cout<<" Configuration of Your Module:-"<<endl;
			cout<<"1.)Land Properties Configuration:-"<<endl<<"10000Sqrfts"<<endl<<"15000Sqrfts"<<endl<<"20000Sqrfts"<<endl<<"30000Sqrfts"<<endl;
	        cout<<"2.)Home  Properties Configuration:-"<<endl<<"1000Sqrfts"<<endl<<"1500Sqrfts"<<endl<<"2000Sqrfts"<<endl<<"3000Sqrfts"<<endl;
			cout<<"3.)Rented  Flat  Configuration:-"<<endl<<"1BHK"<<endl<<"2BHK"<<endl<<"3BHK"<<endl<<"4BHK"<<endl;
			cout<<"==============================================================================================================================="<<endl;
			cout<<"Enter 1 for Land Properties Configuration"<<endl;
			cout<<"Enter 2 for Home Properties Configuration"<<endl;
			cout<<"Enter 3 for  Rented Flat Configuration"<<endl;
			cout<<"==============================================================================================================================="<<endl;
			cout<<"enter which Property or Home or Flat Configuration:- ";
			cin>>q;
		switch(q)
			{
			case 1:
			{
			    int r;
		    cout<<"==============================================================================================================================="<<endl;
			cout<<"Land Properties Configuration:-"<<endl<<"10000Sqrfts"<<endl<<"15000Sqrfts"<<endl<<"20000Sqrfts"<<endl<<"30000Sqrfts"<<endl;
			cout<<"==============================================================================================================================="<<endl;
		    cout<<"Enter How much Square Feets You want from  the given above Static Data :-"<<endl;
			cin>>r;
			cout<<"==============================================================================================================================="<<endl;
			if(r==10000||r==15000||r==20000||r==30000)
			{
			cout<<"The Budget for Buying Land Property in this Area ranges from:-"<<endl;
			cout<<"Rs"<<(r*1500000)<<ends<<"-"<<"Rs"<<(r*17000000)<<endl;
				}
			cout<<"==============================================================================================================================="<<endl;
	               break;
				   }
				   default : 
				   {
				   cout<<"Invalid Input";	
					break;
				   }
				case 2:
			{
			 int s;
			cout<<"Home  Properties Configuration:-"<<endl<<"1 Floor House with 1BHK"<<endl<<"2 Floor House with 2BHK"<<endl<<"3 Floor House with 3BHK"<<endl<<"4 Floor House with 4BHK"<<endl;
			cout<<"==============================================================================================================================="<<endl;
            cout<<"Enter The Number of Floor you need:-"<<endl;
			cin>>s;
			cout<<"==============================================================================================================================="<<endl;
			if(s==1||s==2||s==3||s==4)
			{
			cout<<"The Budget for Buying A Home in this Area ranges from:-"<<endl;
			cout<<"Rs"<<ends<<(s*15000000)<<ends<<"-"<<"Rs"<<ends<<(s*1700000)<<endl;
				}
			cout<<"==============================================================================================================================="<<endl;
				break;
				}
			case 3:
			{
			int u;
			cout<<"Rented Home Properties Configuration:-"<<endl<<"1BHK"<<endl<<"2BHK"<<endl<<"3BHK"<<endl<<"4BHK"<<endl;
			cout<<"==============================================================================================================================="<<endl;
			cout<<"Enter the Number of Rooms:- "<<endl;
			cin>>u;
			cout<<"==============================================================================================================================="<<endl;
			if(u==1||u==2||u==3||u==4)
			{
			cout<<"The Budget for Renting A Flat in this Area ranges from:-"<<endl;
			cout<<"Rs"<<ends<<(u*3000)<<ends<<" - "<<"Rs"<<ends<<(u*5000)<<endl;
				}
				break;
			       }
			   }
		}
class form
{ 
      char name[30];
      char fname[30]; 
	  char mname[30];
	  int dob; 
	  int salary;
      int id;
      char nationality[30];
      char wt[30];
      int mb;
      char nom[20];
      char vill[30];
      char po[30];
      char ps[30];
      char dt[];
      char st[30];
      int pc;
      char ap[30];
      char ag[30];
      public: 
      void getdata();
      void display();
      char* search();
  };
    void form::getdata() 
           { 
            cout<<"==============================================================================================================================="<<endl;
            cout<<"*************************************************** SREPCL Registration Form **************************************************"<<endl;
            cout<<"==============================================================================================================================="<<endl;
            cout<<"You Are requested to fill-up the Form....!!!!!"<<endl;
            cout<<"Enter The Name:- "; 
            cin>>name;
			cout<<"Enter Your Father Name:- "; 
            cin>>fname; 
            cout<<"Enter Your Mother Name:- "; 
            cin>>mname; 
            cout<<"Enter Your Date of Date of Birth (e.g:- DD-MM-YYYY):- "; 
            cin>>dob; 
            cout<<" Enter Your Approximate Salary per Year:- "; 
            cin>>salary;
            cout<<"Enter Your Adhaar Card Number or Pan Card Number:- "; 
            cin>>id;
            cout<<"Enter Your Nationality ( e.g:- Indian Or NRI ):- "; 
            cin>>nationality;
            cout<<"Name Any Witness Person:- "; 
            cin>>wt;
            cout<<"Enter Your Phone number:- "; 
            cin>>mb;
            cout<<"Enter Your Nominee:- "; 
            cin>>nom;
            cout<<"Enter Your Village or City Name:- "; 
            cin>>vill;
            cout<<"Enter Your Post Office:- "; 
            cin>>po;
            cout<<"Enter Your Police Station:- "; 
            cin>>ps;
            cout<<"Enter Your District:- "; 
            cin>>dt;
            cout<<"Enter Your State:- "; 
            cin>>st;
            cout<<"Enter Your Pin Code (6-Digit):- "; 
            cin>>pc;
            cout<<"Enter Your Residential Proof (i.e Previous Electricity Document Or Current Residential Document  ):- "; 
            cin>>ap;
            cout<<"Enter Your Confirmation with an Agreement with our Company (e.g:- I, hereby agree to buy it from SRECPL.):- "; 
            cin>>ag;
            cout<<"==============================================================================================================================="<<endl;
                  } 
    void form::display() 
        { 
            cout<<"==============================================================================================================================="<<endl;
            cout<<"*************************************************** Details Of The Person ******************************************************"<<endl;
            cout<<"==============================================================================================================================="<<endl;
            cout<<"Name:- "; 
            cout<<name<<endl;
            cout<<"Father Name:- "; 
			cout<<fname<<endl;
            cout<<"Mother Name:- "; 
            cout<<mname<<endl;
            cout<<"Date of Date of Birth (e.g:- DD-MM-YYYY):- "; 
            cout<<dob<<endl;
            cout<<"Phone number:- "; 
			cout<<mb<<endl;
			cout<<"Nationality ( e.g:- Indian Or NRI ):- "; 
			cout<<nationality<<endl;
			cout<<"Adhaar Card Number or Pan Card Number:- "; 
		    cout<<id<<endl;
			cout<<"Nominee:- "; 
            cout<<nom<<endl;
            cout<<"Village or City Name:- "; 
            cout<<vill<<endl;
            cout<<"Post Office:- ";
			cout<<po<<endl; 
            cout<<"Police Station:- "; 
            cout<<ps<<endl;
            cout<<"District:- ";
			cout<<dt<<endl; 
            cout<<"State:- "; 
            cout<<st<<endl;
            cout<<"Pin Code (6-Digit):- ";
			cout<<pc<<endl; 
            cout<<"Approximate Salary per Year:- "; 
            cout<<salary<<endl;
            cout<<"Any Witness Person with Address:- "; 
            cout<<wt<<endl;
            cout<<"Residential Proof (i.e Previous Electricity Document Or Current Residential Document with  photocopy attestation ):- "; 
            cout<<ap<<endl;
            cout<<"Confirmation with an Agreement with our Company (e.g:- I, hereby agree to buy it from SRECPL.):- ";
			cout<<ag<<endl; 
			cout<<"==============================================================================================================================="<<endl;
             } 
                   
    char* form::search() 
        { 
           return name; 
            }  			
int main()
{
	fstream fin("SREPCL.txt",ios::in|ios::out|ios::app|ios::binary);
    if(!fin.is_open())
{
	cout<<"                    Error while Opening The File due to availablity of the Existing File with Same Name"<<endl;
	}
	else
	{
	    cout<<"               **********************File has Opened Successfully**********************"<<endl;
    }
	fin.close();
    cst c;
	do
	   { 
        fstream off;
        off.open("SREPCL.txt",ios::out|ios::app|ios::binary);
        cout<<"          ******************** SUNSHINE REAL ESTATE ENTERPRISES PRIVATE LIMITED ********************"<<endl;
        cout<<"                          ********************** Better Living ********************"<<endl;
cout<<"     *                                                                                  *"<<endl;
cout<<"    ***           **********************************************************           ***"<<endl;
cout<<"   *****          *   ****    *****   *****   ******   ******   *          *          *****"<<endl;
cout<<"  ********        *   *       *   *   *       *        *    *   *          *         ********"<<endl;
cout<<" **********       *   *       *   *   *       *        *    *   *          *        **********"<<endl;
cout<<" ****  ****       *   ****    *****   *****   *        ******   *          *        ****  ****"<<endl;
cout<<" ****  ****       *      *    * *     *       *        *        *          *        ****  ****"<<endl;
cout<<" ****  ****       *      *    *   *   *       *        *        *          *        ****  ****"<<endl;
cout<<" ****  ****       *   ****    *    *  *****   ******   *        *******    *        ****  ****"<<endl;
cout<<" **********       **********************************************************        **********"<<endl;
off<<"          ******************** SUNSHINE REAL ESTATE ENTERPRISES PRIVATE LIMITED ********************"<<endl;
                       off<<"                          ********************** Better Living ********************"<<endl;
off<<"     *                                                                                  *"<<endl;
off<<"    ***           **********************************************************           ***"<<endl;
off<<"   *****          *   ****    *****   *****   ******   ******   *          *          *****"<<endl;
off<<"  ********        *   *       *   *   *       *        *    *   *          *         ********"<<endl;
off<<" **********       *   *       *   *   *       *        *    *   *          *        **********"<<endl;
off<<" ****  ****       *   ****    *****   *****   *        ******   *          *        ****  ****"<<endl;
off<<" ****  ****       *      *    * *     *       *        *        *          *        ****  ****"<<endl;
off<<" ****  ****       *      *    *   *   *       *        *        *          *        ****  ****"<<endl;
off<<" ****  ****       *   ****    *    *  *****   ******   *        *******    *        ****  ****"<<endl;
off<<" **********       **********************************************************        **********"<<endl;
cout<<"==============================================================================================================================="<<endl;
  	c.get();
  	if(c.p == 0)
	  //exit(1);
	off<<"==============================================================================================================================="<<endl;
    off<<"==============================================================================================================================="<<endl;
    off<<"Customer Module"<<endl;
    off<<"1.)Land"<<endl;
    off<<"2.)Home"<<endl;
    off<<"4.)Rented Flat"<<endl;
    off<<"==============================================================================================================================="<<endl;
    off<<"==============================================================================================================================="<<endl;
    off<<"The Various Location Are as follows :- "<<endl;
    off<<"1.) Jalandhar"<<endl;
    off<<"2.) Phagwara" <<endl;  
    off<<"3.) Amritsar"<<endl;
    off<<"4.) Ludhiana"<<endl;
    off<<"5.) Hoshiar Pur"<<endl;
    off<<"==============================================================================================================================="<<endl;
    off<<"==============================================================================================================================="<<endl;
    off<<"Configuration of Your Module:-"<<endl;
    off<<"1.)Land Properties Configuration:-"<<endl<<"10000Sqrfts"<<endl<<"15000Sqrfts"<<endl<<"20000Sqrfts"<<endl<<"30000Sqrfts"<<endl;
    off<<"2.)Home  Properties Configuration:-"<<endl<<"1000Sqrfts"<<endl<<"1500Sqrfts"<<endl<<"2000Sqrfts"<<endl<<"3000Sqrfts"<<endl;
	off<<"3.)Rented Home Properties Configuration:-"<<endl<<"1BHK"<<endl<<"2BHK"<<endl<<"3BHK"<<endl<<"4BHK"<<endl;
	off<<"==============================================================================================================================="<<endl;
	off<<"==============================================================================================================================="<<endl;
	off.close();
	ofstream fout; 
    int i,n=1;
    form  a[50],ap[50];
    fout.open("SREPCL.txt",ios::out|ios::binary|ios::app);
	for(i=0;i<n;i++) 
    { 
        a[i].getdata(); 
        fout.write((char*)&a[i],sizeof(a[i]));
            } 
	fout.close(); 
    char name[20];
    cout<<"Check whether The Form Has Been Filled correctly by Searching His/Her Name:- "; 
    cin>>name; 
    ifstream ff; 
    ff.open("SREPCL.txt",ios::in); 
    //for(i=0;i<n;i++) 
    while(!ff.eof()) 
    { 
    ff.read((char*)&ap[i],sizeof(ap[i])); 
    if(strcmp(name,ap[i].search())==0)
    {
    ap[i].display(); 
    break;
            }
    ff.close();
                 }
    cout<<"        ****************************The Form Has Been filled Properly and According to the Norms of SREPCL*************************"<<endl;
    cout<<"                  ********************************Thank  For Being With Us******************************"<<endl;
    off<<"                           **********************Thank  For Being With Us*************************"<<endl;
    cout<<"                                  ********************Have A Nice Day******************"<<endl;
    off<<"                                      *****************Have A Nice Day***************"<<endl;
    cout<<"                                                                                                                                            For Any Further Enquiry:-"<<endl;
    off<<"                                                                                                                                            For Any Further Enquiry:-"<<endl;
    cout<<"                                                                                                                                         SREPCL Customer Enqury Number:- 8773673245"<<endl;
    off<<"                                                                                                                                          SREPCL Customer Enqury Number:- 8773673245"<<endl;
    cout<<"                                2013 All rights reserved. SUNSHINE REAL ESTATE ENTERPRISES PRIVATE LIMITED.                                     "<<endl;
               
               
    // getch();

	}
	while(c.p != 0);
	return 0;                          
	}
            
            
			 
           
              
            
        
                   
                
     
