# Razorpayflutter

//step1
//add this package to flutter
razorpay_flutter: ^1.2.2

//step2
//add that payment file on your lib


//step3
//ctreate a page there is written like 3 month subscription for 100
//and a subscribe button
//in that button add the below code

onTap(){

var price = 100;
Navigator.push(
        context,
        MaterialPageRoute(
            builder: (context) => CheckRazor(
                  price: price,
                )));
                
     }
     
     
     
