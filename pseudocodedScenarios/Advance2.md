<!-- You're building an activity feed for a social media site. The feed must display a chronological list of activities for the current user's friends. These activities could potentially be any action performed on the site including uploading a photo, changing their profile, friending another user, commenting, liking etc... Further, you only want to display activities for users that the current user interacts with frequently. -->

##User

*Friends*
* Sorted by recent activity date only with Frequency = true
{
  *Frequency of interacting: boolean*
  * true or false
  *Friend name: string*
  * Up to 40 characters
  *Activitys*
  * Sorted by date
    *uploading a photo*
      *date/time*
      * Date and time
      *content*
      * content of photo
    *changing their profile*
      *date/time*
      * Date and time
      *content*
      * content of change
    *friending another user*
      *date/time*
      * Date and time
      *content*
      * content of friending
    *commenting*
      *date/time*
      * Date and time
      *content*
      * content of commenting
    *liking*
      *date/time*
      * Date and time
      *content*
      * content of liking
}
