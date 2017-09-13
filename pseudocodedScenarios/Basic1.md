<!-- You're building an application that requires user login. Once logged in the user has a bunch of profile information and preference settings available to them. They will need to be able set their birthday, gender, phone number and location (city, state, country). They should be able to provide text to tell about themselves. They also should be able to enable and disable visibility of their birthday, gender, phone number and location. -->

##users

*username: String*
    * Must contain only word characters
*password: String*
    * Must be at least 8 characters
*profile*
  *private or public: boolean*
    * True or false
  *Tell about self: text*
    * Up to 200 characters
  {
    *birthday: Date*
      * eg. 10/05/1999
    *gender: String*
      * Up to 15 characters
    *phone number: Number*
      * Up to 15 digits*
    *location*
      {
        *city: String*
          * Up to 40 characters
        *state: String*
          * 2 characters only
        *country: string*
          * Up to 50 characters
      }
  }
