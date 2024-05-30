## OTP Generator
This repository contains a simple JavaScript function to
generate One-Time Passwords (OTPs) using a random combination of digits.

## How it Works
The generateOTP function in script.js generates a random 6-digit OTP by iterating 
through a string of digits from 0 to 9 and appending a random digit to the OTP string in each iteration.

## Usage
To use the OTP generator in your project:

Copy the generateOTP function from script.js into your project.
Call the generateOTP function whenever you need to generate an OTP.

## ex
var otp = generateOTP();
console.log("Your OTP is: " + otp);
