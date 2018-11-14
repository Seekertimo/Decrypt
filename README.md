# Decrypt
SEC

opdracht 1: 
- <?php
$hashed_password = crypt('mypassword'); // let the salt be automatically generated

/* You should pass the entire results of crypt() as the salt for comparing a
   password, to avoid problems when different hashing algorithms are used. (As
   it says above, standard DES-based password hashing uses a 2-character salt,
   but MD5-based hashing uses 12.) */
if (hash_equals($hashed_password, crypt($user_input, $hashed_password))) {
   echo "Password verified!";
}
?>

-  <?php
// Set the password
$password = 'mypassword';

- // Get the hash, letting the salt be automatically generated
 $hash = crypt($password);
?>
        
- <?php
/* These salts are examples only, and should not be used verbatim in your code.
   You should generate a distinct, correctly-formatted salt for each password.
*/
if (CRYPT_STD_DES == 1) {
    echo 'Standard DES: ' . crypt('rasmuslerdorf', 'rl') . "\n";
}
    
    
    
    
    Opdracht 2:
    
    RSA heeft een data limiet van 245/256 (een van de twee maar weet  niet zeker)
    
    
    
    
    
    Opdracht 3
    
    - Ik maar gebruik van een UN en Password combinatie.
    - Met een SSH kan je met Github connecten zonder je username of password in te vullen.
