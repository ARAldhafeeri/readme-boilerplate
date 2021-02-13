# readme-boilerplate
Here you find organized README.MD boilerplate with most of the markup language syntax, also some tools to help you to be a documentation master. As front-end and documentation are time consuming but they are as curtail and valuable as fully functional app or a backend because they consider the users and by users I mean both (clients and developers who are working on the team ) 
## Very helpful github for markup and readme.md files:
> https://github.com/matiassingers/awesome-readme

<a href="https://github.com/ARAldhafeeri/">
  <img align="right" width="100" height="100" alt="Official Javascript Component" src="https://cdn2.iconfinder.com/data/icons/font-awesome/1792/code-512.png">
</a>

# boilerplate

![packge-name](https://img.shields.io/github/license/ARAldhafeeri/readme-boilerplate.png)

> sentance descripte the package.

<!-- page index example -->

- [Introduction](#introduction)
    + [Introduction section 1](#introduction-section-1)
    + [Introduction section 2](#introduction-section-1)
- [Get started](#get-started)
- [Installation](#installation)
- [Examples](#examples)
  * [Example with code javascript](#example-with-code-javascript)
  * [Example with code Python](#example-with-code-python)
  * [Badges](#get-github-repo-package-badge)
  * [Color](#color)
    + [sub section](#sub-section-1) 
    + [sub section](#sub-section-2)
    

<!-- introduction -->

## Introduction

Hey this is a brief introduction to our package

#### Want to learn more ?

Well here we will write for you more details about our app. Please check the link below for more details

#### introduction section 1


Well here we will write for you more details about our app. Please check the link below for more details

#### introduction section 2


Well here we will write for you more details about our app. Please check the link below for more details


> https://www.example.com

#### Get started

here we are going to share more details about how to get started with our package. Below is a link for more on how to get started.

> https://www.example.com

#### Learn even more about our package

Here we are going to share detailed description about our packge. Check link below.

> https://www.example.com

## installation

 installation commands
```
$ npm i --save [package-name1]
$ npm i --save [package-name2]
$ npm i --save [package-name3]
$ npm i --save [package-name4]
```

- explain the commands ? yay fun.
  * ``` npm i --save [package-name1] ``` 
    + explain what the command 
  * ``` npm i --save [package-name2] ``` 
    + explain what the command
  * ``` npm i --save [package-name2] ``` 
    + explain what the command
  * ``` npm i --save [package-name2] ``` 
    + explain what the command


# Examples 

#### Example with code javascript

Here is an introduction & some code example on how to use the package.

```javascript
import {CardElement, Elements, ElementsConsumer} from '@stripe/react-stripe-js';
import {loadStripe} from '@stripe/stripe-js';
import React, {Component} from 'react';
import CheckoutForm from "../Components/CheckoutForm

const InjectedCheckoutForm = () => (
<Elements stripe={stripePromise}>
        <ElementsConsumer>
        {({stripe, elements}) => (
            <CheckoutForm stripe={stripe} elements={elements}  />
        )}
        </ElementsConsumer>
</Elements>
);

export default InjectedCheckoutForm;
```

#### Example with code python

Here is an introduction & some code example on how to use the package.

```python
# Depndency Injection
###############################################################################
"""
very good mechanism of implementing loose couplings,
and it helps make our application maintainable and extendable.
The advantage is that encapsulating actions in such a way enables Python
developers to add additional functionalities related to the executed actions,
such as undo/redo, or keeping a history of actions and the like.
"""
# Inject dependencies through the constructor
class Command:
  def __init__(self, authenticate=None, authorize=None):
      self.authenticate = authenticate or self._not_authenticated
      self.authorize = authorize or self._not_autorized
   def execute(self, user, action):
      self.authenticate(user)
      self.authorize(user, action)
      return action()

if in_sudo_mode:
    command = Command(always_authenticated, always_authorized)
else:
    command = Command(config.authenticate, config.authorize)
    command.execute(current_user, delete_user_action)

# Inject dependencies by setting directly the object properties
command = Command()
if in_sudo_mode:
  command.authenticate = always_authenticated
  command.authorize = always_authorized
else:
  command.authenticate = config.authenticate
  command.authorize = config.authorize
command.execute(current_user, delete_user_action)

```
# Get github repo package badge
> https://shields.io/
#### copy and paste your repo link, it will give you suggessions. Then make your own padges as explained on the website


#### Table markup example
|                                                             | Name              | GitHub                                               |
| :---------------------------------------------------------: | ----------------- | ---------------------------------------------------- |
| <img src="https://github.com/araldhafeeri.png?size=72" />   | araldhafeeri      | [@araldhafeeri](https://github.com/araldhafeeri)     |
| <img src="https://github.com/araldhafeeri.png?size=72" />   | araldhafeeri      | [@araldhafeeri](https://github.com/araldhafeeri)     |

