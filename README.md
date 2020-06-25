# conversao_base

<script>
dec_para_binario  = function(n, base) {

 if (n < 0) {
   n = 0xFFFFFFFF + n + 1;
  } 
switch (base)  
{  
case 'Binario':  
return parseInt(n, 10).toString(2);
break;  
default:  
return("Wrong input.........");  
}  
}

var n = prompt("Digite um valor: ");
document.write(dec_para_binario(n,'Binario'));
console.log(dec_para_binario(45,'Binario'));
</script>
