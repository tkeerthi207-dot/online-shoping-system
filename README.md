# online-shoping-system
online shoping system diskription Online Shopping System – Description 1. Introduction An Online Shopping System is a web-based application that allows customers to buy products through the internet. Customers can view products, select items, add them to the shopping cart, and purchase products from anywhere.  2. Objectives To make shopping easy an
vonline shoping system diskription
Online Shopping System – Description
1. Introduction
An Online Shopping System is a web-based application that allows customers to buy products through the internet. Customers can view products, select items, add them to the shopping cart, and purchase products from anywhere.

2. Objectives
To make shopping easy and convenient.

To save customers' time.

To provide different types of products.

To allow online payments.

To deliver products to customers' homes.

3. Main Feature
#include <stdio.h>

int main()
{
    int choice, quantity;
    float total = 0;

    printf("===== ONLINE SHOPPING SYSTEM =====\n");

    printf("\nAvailable Products:\n");
    printf("1. Laptop       - Rs. 50000\n");
    printf("2. Mobile       - Rs. 20000\n");
    printf("3. Headphones   - Rs. 1000\n");
    printf("4. Keyboard     - Rs. 800\n");
    printf("5. Mouse        - Rs. 500\n");

    printf("\nEnter your product choice: ");
    scanf("%d", &choice);

    printf("Enter quantity: ");
    scanf("%d", &quantity);

    switch(choice)
    {
        case 1:
            total = 50000 * quantity;
            break;

        case 2:
            total = 20000 * quantity;
            break;

        case 3:
            total = 1000 * quantity;
            break;

        case 4:
            total = 800 * quantity;
            break;

        case 5:
            total = 500 * quantity;
            break;

        default:
            printf("Invalid product choice!\n");
            return 0;
    }

    printf("\n===== BILL DETAILS =====\n");
    printf("Quantity: %d\n", quantity);
    printf("Total Amount: Rs. %.2f\n", total);

    printf("\nThank you for shopping!\n");v===== ONLINE SHOPPING SYSTEM =====

Available Products:
1. Laptop       - Rs. 50000
2. Mobile       - Rs. 20000
3. Headphones   - Rs. 1000
4. Keyboard     - Rs. 800
5. Mouse        - Rs. 500

Enter your product choice: 2
Enter quantity: 2

===== BILL DETAILS =====
Quantity: 2
Total Amount: Rs. 40000.00

Thank you for shopping!

    return 0;
}
