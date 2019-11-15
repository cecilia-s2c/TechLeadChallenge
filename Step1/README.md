  - The app could use a newer version of Meteor. Among other things,
    newer versions of Meteor will tend to be more secure. We have
    updated Meteor in our branch.

  - It could be a good idea to not hardcode a password as in line \#34
    of `client/main.js`. These secrets should be stored in a settings
    file that's passed as an argument to the meteor invocation. In
    `server/twitter.js` the secrets needed to use the Twitter API are
    already set up with this technique. See:
    <https://guide.meteor.com/security.html#api-keys>

  - The http function can take in an `auth` option. Depending on the
    setup of `secure.safe2choose.org`, this could be used for
    authentication. See: <https://docs.meteor.com/api/http.html>

  - Even if the counter seems to be entirely controlled by the app, it
    could be a good idea to validate that it is indeed an integer before
    sending it to secure.safe2choose.org.

  - The `counts.set` method defined in `server/counts-methods.js`
    doesn't do any validation either. This method writes to the MongoDB
    database and it's important that it does some validation. It should
    not be hard to fix this using the `mdg:validated-method` package.
    See: <https://guide.meteor.com/methods.html#validated-method>
