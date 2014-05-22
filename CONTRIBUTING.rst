If you would like to contribute to the development of OpenStack,
you must follow the steps in the "If you're a developer, start here"
section of this page:

   http://wiki.openstack.org/HowToContribute

Once those steps have been completed, changes to OpenStack
should be submitted for review via the Gerrit tool, following
the workflow documented at:

   http://wiki.openstack.org/GerritWorkflow

Pull requests submitted through GitHub will be ignored.

Bugs should be filed on StoryBoard, not GitHub:

   https://storyboard.openstack.org/#!/project/718

To browse the latest code:

   https://git.openstack.org/cgit/openstack-infra/gerritlib/tree/

To clone the latest code:

   git clone git://git.openstack.org/openstack-infra/gerritlib

Code reviews are handled by gerrit:
   http://review.openstack.org

Use `git review` to submit patches (after creating a gerrit
account that links to your launchpad account). Example::

    # Do your commits
    $ git review
    # Enter your username if prompted
