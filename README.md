#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <ctype.h>  // For checking if a character is a digit

struct BankAccount {
    int accountNumber;
    char accountHolderName[100];
    char phonenumber[11];  // 10 digits + 1 for null terminator
    char email[50];  // Increased size for email
    char address[100];
    float balance;
};
