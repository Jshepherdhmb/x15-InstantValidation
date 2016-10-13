function validate(){
  //Grab the user's input and store in variables
  var userEntered = document.getElementById("user").value;
  var passEntered = document.getElementById("pass").value;
  var password = "password"
if(userEntered.length < 6 || userEntered.indexOf(' ') > 0 || userEntered == passEntered){

  //Show message that there is an error with the username...
  	document.getElementById("usernameError").innerHTML="Bad username.";
 	document.getElementById("usernameError").classList.remove("hidden-message");
  	document.getElementById("usernameError").classList.add("shown-message");
  //Turn the username items red
 	document.getElementById("usernameGroup").classList.add("has-error");
}else if (userEntered.length >= 6 && userEntered.indexOf(' ') < 1 && userEntered !=passEntered){
 //Turn the username items to green
	document.getElementById("usernameGroup").classList.add("has-success");
}
if (passEntered.length < 6 || passEntered == "password"|| passEntered == "PASSWORD" ||  userEntered == passEntered || passEntered.length > 20 || userEntered.toUpperCase == passEntered.toUpperCase || userEntered.toLowerCase == passEntered.toLowerCase) {
  //Show message that there is an error with the password...
  	document.getElementById("passwordError").innerHTML="Bad password.";
 	 document.getElementById("passwordError").classList.remove("hidden-message");
 	 document.getElementById("passwordError").classList.add("shown-message");
  //Turn the password items red
 	 document.getElementById("passwordGroup").classList.add("has-error");
}
else if (passEntered.length >= 6 && passEntered != "password" && passEntered != "PASSWORD" && passEntered.length <= 20 && userEntered.toUpperCase != passEntered.toUpperCase && userEntered.toLowerCase != passEntered.toLowerCase){
  //Turn the password items green

 	 document.getElementById("passwordGroup").classList.add("has-success");
}
}
