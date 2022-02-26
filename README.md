# Contact
 #I created an application that will create unit tests to uncover errors for mobile applications.

#I did well in the application but this code give quick summary of how well.

protected void updateFirstName(String firstName) {
if (firstName == null) {
throw new IllegalArgumentException("First name cannot be empty");
} else if (firstName.length() > CONTACT_FNAME_LENGTH) {
throw new IllegalArgumentException(
"First name cannot be longer than " + CONTACT_FNAME_LENGTH + " characters");
} else {
this.firstName = firstName;
}
}

#I found this code to be a bit challenging when including Junit test which I have never done before. I overcame this by plenty of research and learning exactly how these work which helped me get through it.
to help me with this project I used resources I was provided through SNHU and also Codecademy was a big help as well.

#The skills that will transfer over to other projects will be testing and creating classes.
