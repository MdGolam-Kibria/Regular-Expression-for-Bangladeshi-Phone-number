# Regular-Expression-for-Bangladeshi-Phone-number
This is regular expression for bangladeshi phone number :-

<h1>regexp =  "^(?:\\+88|01)?\\d{11}$"</h1>

- Like in spring boot : =

`
@Pattern(regexp = "^(?:\\+88|01)?\\d{11}$", message = "invalid mobile number.")
    @Size(max = 11, message = "digits should be 10")
    private String mobile;
`


