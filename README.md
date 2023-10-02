- punto uno scaricare il file da classroom e rinominarlo adeguatamente come è sritto nella consegna
- punto due aprire il file su Visual studio code
- ora incominciamo a svolgere l esercizio seguendo la consegna

- Come prima cosa per scorrere ogni elemento dentro l' array usiamo il foreach\

  foreach (var num in vettore){}

- All' interno richiamiamo il metodo IsnumeroTelefonoItaliano e si controlla che num sia valido\

  if (IsnumeroTelefonoItaliano(num))
      {
         return num;
      }
- Adesso si creano dei metodi che verificano le caratteristiche che un numero di telefono deve avere\
- così verifichiamo i prefissi e la lunghezza della stringa se torna true vuol dire che è valida\

  if (num.Lenght == 13&& (num.Startswith("+39"))
      {
         return true;
      }

- concludiamo eseguendo gli altri due modelli\

if (num.Lenght == 14 && num.Startswith("0039"))
   {
         return true;
   }

if (num.Lenght == 10 && num.Startswith("3"))
   {
         return true;
   }

- se le condizioni non vengono rispettate nella stringa ritorna false e quindi il numero risulta non valido
  

   
