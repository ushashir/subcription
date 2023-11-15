# SUBSCRIPTION. A TASK BY BRIGHT

## Subscription-based Business
### Objective:
- The goal of this assignment is to model a subscription-based business where users
subscribe to different plans.
- Instructions:
Create an interface: Subscribable
- Define a method calculateSubscriptionCost() to calculate the cost of the subscription based
on the implementing class.
- Create an enum: SubscriptionType
- Define subscription types such as BASIC, STANDARD, and PREMIUM.

### Create a class: User
- Include properties like user ID, name, email, and a reference to the subscribed plan.
Implement methods for user-related functionalities, e.g., displaying user information.

### Create an abstract class: SubscriptionPlan
Implement the Subscribable interface.
Include properties like plan ID, name, and cost.
Create a constructor that initializes these properties.
Provide a default implementation for calculateSubscriptionCost().
Create concrete classes: BasicPlan, StandardPlan, and PremiumPlan
Extend SubscriptionPlan.
Override the calculateSubscriptionCost() method with specific pricing for each plan.
Create a class: BusinessModel
In the main method, create instances of User and different subscription plans.
Associate users with subscription plans.
Display user information and the cost of their subscriptions.

### Constraints:
Ensure proper encapsulation and use access modifiers where appropriate.
Validate input for user information and subscription costs.
Utilize appropriate data types for user details and subscription information.

### Bonus (Optional):
Implement a mechanism to upgrade or downgrade a user's subscription plan.
Include features for handling subscription renewals and expirations.
Introduce a concept of promotions or discounts based on certain conditions.
Submission:
Submit the Java source code files.
Include a brief explanation of your design choices and any challenges faced during
implementation.

This assignment provides students with a practical scenario where they can apply the
principles of interfaces, abstractions, and inheritance to model a subscription-based
business, which is a common model in various industries today. It also allows for creativity in
extending the functionality of the system.
