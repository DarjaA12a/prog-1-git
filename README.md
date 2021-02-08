
Scanner input = new Scanner(System.in);
        int amount_number_of_tshirt;
        amount_number_of_tshirt = input.nextInt();
        String prints;
        prints= input.next();
        int formula = amount_number_of_tshirt*5;
        int formula2 = amount_number_of_tshirt*7;
        int formula3 = amount_number_of_tshirt*20;
        if("TEXT".equals(prints)||"text".equals(prints)){
           
            System.out.println("fee for t-shirts "+formula);
        
        if(formula>=50){
            System.out.println("free charge from delivery");
        }else{
                            System.out.println("additional payment 15 EUR for delivery because amount is less then 50 euro");

        }
           
            
            
        
            
            
        }
        if("draw".equals(prints)||"draw".equals(prints)){
            System.out.println("fee for t-shirts "+formula2);
            
            if(formula2>=50){
            System.out.println("free charge from delivery");
            }else{
                System.out.println("additional payment 15 EUR for delivery because amount is less then 50 euro");
            }
            }
                if( "PHOTO".equals(prints)||"photo".equals(prints)){
           
            System.out.println("fee for t-shirts "+formula3);
            if (formula3>=50) {
                    System.out.println("free charge from delivery");
                }else{
                System.out.println("additional payment 15 EUR for delivery because amount is less then 50 euro");
            }
        }
         
            
        if(formula==100||formula2==100||formula3==100){
                int discount= 5*(amount_number_of_tshirt/100);
                System.out.println("%5 discount congrats"+discount);
              }  