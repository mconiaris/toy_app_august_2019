Place in Tutorial:

2.2.3 Weaknesses of this Users resource
https://www.railstutorial.org/book/toy_app#sec-weaknesses_of_this_users_resource


======================
# REpresentational State Transfer (REST)
If you read much about Ruby on Rails web development, you’ll see a lot of references to “REST”, which is an acronym for REpresentational State Transfer. REST is an architectural style for developing distributed, networked systems and software applications such as the World Wide Web and web applications. Although REST theory is rather abstract, in the context of Rails applications REST means that most application components (such as users and microposts) are modeled as resources that can be created, read, updated, and deleted—operations that correspond both to the CRUD operations of relational databases and to the four fundamental HTTP request methods: POST, GET, PATCH, and DELETE. (We’ll learn more about HTTP requests in Section 3.3 and especially Box 3.2.)

As a Rails application developer, the RESTful style of development helps you make choices about which controllers and actions to write: you simply structure the application using resources that get created, read, updated, and deleted. In the case of users and microposts, this process is straightforward, since they are naturally resources in their own right. In Chapter 14, we’ll see an example where REST principles allow us to model a subtler problem, “following users”, in a natural and convenient way.