# Regular-Expression-for-Bangladeshi-Phone-number
This is regular expression for bangladeshi phone number :-

<h1>regexp = "^(?:\\+?88)?01[135-9]\\d{8}$"</h1>

- Like in spring boot : =

`
 @Pattern(regexp = "^(?:\\+?88)?01[135-9]\\d{8}$", message = "invalid mobile number.")
    @Size(max = 11, message = "digits should be 11")
    private String mobile;
`
### Here:-

- ^ - From start of the string.

- (?:\+?88)? - optional 88, which may begin in +

- 01 - mandatory 01

- [135-9] - "1 or 3 or 5 or 6 or 7 or 8 or 9"

- \d{8} - 8 digits

- $ - end of the string

