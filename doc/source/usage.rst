=====
Usage
=====

Example usage::

    import gerritlib.gerrit as gerrit
    g = gerrit.Gerrit('gerrit_host', 'username', keyfile='/home/username/.ssh/id_rsa.pub')

    # manage projects
    g.createProject('test', description='a test project')
    projects = g.listProjects()
    print(projects)

    # manage groups
    g.createGroup('testers')
    groups = g.listGroups()
    print(groups)


Look at the :doc:`api` for more details.