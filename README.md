# Abstract-Classes-and-Abstract-Methods
**Patient Payment System**

This program is a simple implementation of a patient payment system. It has three classes: ***'Patient'***, ***'RegularPatient'***, and ***'InstantPatient'***.

**Patient**

The ***'Patient'*** class is an abstract class that represents a patient. It has three properties:

-***first_name***: the patient's first name

-***last_name***: the patient's last name

-***ssn***: the patient's social security number

It also has an abstract method called payment, which raises a NotImplementedError. This means that any class that inherits from Patient must implement the payment method.

**RegularPatient**

The ***'RegularPatient'*** class represents a regular patient who has a fixed weekly salary. It inherits from the ***'Patient class'*** and has an additional property:

-***weekly_salary***: the patient's weekly salary

It implements the payment method by returning the value of ***'weekly_salary'***.

**InstantPatient**

The ***'InstantPatient'*** class represents an instant patient who is paid by the hour. It also inherits from the ***'Patient'*** class and has two additional properties:

-***'hours'***: the number of hours the patient worked

-'***payment_per_hour'***: the patient's payment per hour

It implements the ***'payment'*** method by returning the product of ***'hours'*** and ***'payment_per_hour'***.




