# Customer Redis Example

This repo is used for the customer engineer exercise.
Instructions can be found at https://gist.github.com/jmacelroy/583831a3643eaac769f0d4cda2fd837d.

The prompt for the exercise can be found [here](PROMPT.md)

You can answer the questions from the prompt and complete the demo by creating a fork where you'll make your modifications before sharing.

## Prompt

The exercise consists of the following parts.

### How would you initially respond to the customer?
Dear Alice,

Thank you for reaching out to us with your concerns. We would be happy to help you get your team setup to work on the new service.

- Next steps:

Our first step would be to clone the repository you provided in your email, https://github.com/okteto/customer-redis-example, and familiarize ourselves with the code and the issues you encountered.

- Completing the demo:

After reviewing the code and the repository, we have added a docker-compose file and an okteto manifest to the repository. 
The demo can now be run successfully on the cluster where your access has been provisioned, and you should be able to use the application as intended.

### What would your next steps be after reading their email and responding?
Please see above

### Summarize what work was needed for completing the demo for the customer.
In summary, 
we have completed the demo by adding a docker-compose file and an okteto manifest to the repository provided (I ran "okteto init" to configure okteto.yml). 
To run the demo, you can simply use the "docker-compose up" command, and the application should start as intended. 
You can find more information on how to run docker-compose and okteto in our [documentation](https://www.okteto.com/docs/welcome/overview/).

### What improvments can Okteto make to better support this, or similar, customers in the future.
I would suggest that Okteto consider providing more comprehensive documentation and examples for setting up and using Redis with Okteto, to make it easier for customers to get started. 
Additionally, providing templates for common use cases, such as a Redis setup, could also be beneficial to customers.
