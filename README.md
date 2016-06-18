# Mobile login
A secure password"less" login method inspired by mobile bank id

In Sweden, you can login into bank system or gov's platform through an authentication method called Bank ID. They also got an mobile version of it namely mobile Bank ID.
The way to login is to:

1. first, type your personal number into the login field.
2. open your mobile app and "sign" the login request (which is a simple click).
3. you are logged in! No password is needed except the one on the phone to prevent unauthorized access to the app.

# Problem of current 2FA
So, these days, we keep on forgetting our password. It is some how difficult for people to remember a brunch of password for different applications.

OTP over SMS is not secure at all, as the SS7 has its own vulnerability and the government can simply ask for telecom provider to redirect the code to the agent.

OTP over APP generator is an alternative solution but still require us to type the code on the browser, which is not a good solution for laymen. 

# How we do it? (TODO)
TODO

# Forking it?
Or better say implementing a similar solution for the open source world.
We can use technology like asymmetric cryptography to achieve the signing and create a protocol  for systems to utilise this protocol for better authentication. 




