# Southbank Centre App: Header

## Installation

### Step 1
Run the following command in your app's root directory.

    $ bower install --save Southbank-Centre/SC-app-header#n.n.n

Replace n.n.n with the version number of this module that you require. See [the list of releases](https://github.com/Southbank-Centre/SC-app-festival/releases).

*Please don't install without a release number or your app will be unstable.*

### Step 2
Add the header view to the **app** state:

    .state('app', {
        url: '',
        views: {
            ...
            'header' : {
                templateUrl: 'bower_components/SC-app-header/release/headerView.html'
              }
            ...
        }
    }