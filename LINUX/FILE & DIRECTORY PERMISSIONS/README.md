# File and Directory Permissions:

In Linux, each file and directory has three sets of permissions: one for the owner, one for the group, and one for others.

  #  Permissions:
        Read (r): Allows the reading of the file's contents or viewing of a directory's contents.
        Write (w): Permits the modification of a file's content or the addition/removal of files within a directory.
        Execute (x): Grants the execution of a file or allows access to a directory.

   # Permission Types:
        Owner (u): The user who owns the file or directory.
        Group (g): The group associated with the file or directory.
        Others (o): Any other user who has access to the system.

    #  Numeric Representation:
        Permissions are often represented numerically: read (4), write (2), execute (1).
        The sum of these numbers represents the total permission. For example, read and write would be 6 (4 + 2).

    # Changing Permissions:
        The chmod command is used to change permissions.
        Syntax: chmod [options] permissions file/directory

    # Viewing Permissions:
        The ls command with the -l option shows detailed information, including permissions.
        Example: ls -l file.txt

    # Changing Ownership:
        The chown command is used to change ownership.
        Syntax: chown [options] new_owner:new_group file/directory

    # Changing Group:
        The chgrp command is used to change the group.
        Syntax: chgrp new_group file/directory

