import java.util.scanner,
class Middle
{
int noDigit=(int)Math.log10(num)+1;
if(noDigit%2==0)
  return-1;
else
{
   int divisor=(int)Math.pow(10,noDigit/2);
   int Middle=(num/divisor)%10;
   return Middle;
}
Public Static void main(String args[])
{
Scanner ip=new Scanner(System.in);
int num=ip.nextInt();
int res=find Middle(num);
if(res==-1)
System.out.println("There is a no middle digit");
else
System.out.println(res);
}
}
   
