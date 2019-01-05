# Jarak-tempuh


                  #include <iostream>
                  using namespace std;
                  int main()
                  {
                  int pil;
                  float s,t,d;

                  cout << "|=====================================================|" << endl;
                  cout << "|===================== ALIF MUSTAFANAH ===============|" << endl;
                  cout << "|========================= WELCOME ===================|" << endl;
                  cout << "|=====================================================|\n" << endl;
                  atas :
                  cout << "PILIH RUMUS :\n" << endl;
                  cout << "1. Jarak tempuh" << endl;
                  cout << "2. kecepatan" << endl;
                  cout << "3. Waktu tempuh" << endl;
                  cout << "4. EXIT\n";
                  cout << "\nPilihan anda : ";
                  cin>>pil;
                  switch (pil)
                  {
                  case 1:
                  cout << "------------------------------------------------------|\n" << endl;
                  cout<<"Masukkan kecepatan (km/jam) : ";
                  cin>>s;
                  cout<<"Masukkan Waktu tempuh (jam) : ";
                  cin>>t;
                  cout<<"Jarak yang anda tempuh adalah "<<s*t<<" KM"<<endl;
                  cout << "-----------------------------------------------------|\n" << endl;
                  break;
                  case 2:
                  cout << "-----------------------------------------------------|\n" << endl;
                  cout<<"Masukkan jarak tempuh (km) : ";
                  cin>>d;
                  cout<<"Masukkan Waktu tempuh (jam): ";
                  cin>>t;
                  cout<<"Kecepatan tempuh anda adalah "<<d/t<<" km/jam"<<endl;
                  cout << "-----------------------------------------------------|\n" << endl;
                  break;
                  case 3:
                  cout << "-----------------------------------------------------|\n" << endl;
                  cout<<"Masukkan jarak tempuh (km)  : ";
                  cin>>d;
                  cout<<"Masukkan kecepatan (km/jam) : ";
                  cin>>s;
                  cout<<"Waktu tempuh anda adalah "<<d/s<<" jam"<<endl;
                  cout << "-----------------------------------------------------|\n" << endl;
                  break;
                  case 4:
                  cout << "|=====================================================|" << endl;
                  cout << "|===================== ALIF MUSTAFANAH ===============|" << endl;
                  cout << "|======================= TERIMAKASIH =================|" << endl;
                  cout << "|=================== PRESS ENTER TO EXIT =============|" << endl;
                  cout << "|=====================================================|" << endl;
                  return 0;
                  break;
                  default:
                  cout<<"Pilihan anda tidak tersedia"<<endl;
                  break;

                  }
                  goto atas;
                  }
