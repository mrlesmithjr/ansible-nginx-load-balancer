commit 64568550e3f89a5464beb0cd35c7c99ce762817f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Mar 14 22:30:38 2020 -0400

    Fixing Molecule testing

commit 7b82e6ca75f93e3814247f7dc47aa3a63f26eae4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Mar 14 22:24:14 2020 -0400

    Fixing test converge playbook

commit df0b2b2187d8df5c5bf43fa53ba527ef16ff4d6d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Mar 14 22:15:07 2020 -0400

    Added: New functionality for defining multiple locations

commit eceaa2ba7d6c2093123c3d50002d99225ac377cd
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 13 01:01:29 2020 -0400

    Updated: changelog

commit c297a80aca6ea133ebbd07fe3e08d94c61e55527
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Mar 13 01:00:52 2020 -0400

    Updated: Removed headers config
    
    Removed headers config and moved to options to allow more control

commit 9c9928487529b84c19640894fdc98de9493cd089
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Feb 23 00:50:28 2020 -0500

    Disabled Ubuntu 16.04 tests
    
    - There is an issue with pyopenssl pip install currently
    - Will investigate later

commit 4bcde351dbbf333007d5659df8113c15d34b9739
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Feb 23 00:18:36 2020 -0500

    Added an additional config for HTTP LB

commit 7318c035dc380d83c7da042263c994bc893b879d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Feb 23 00:18:14 2020 -0500

    Added required role ansible-bootstrap-python
    
    - This role ensures Python is setup correctly to ensure pip modules can be installed

commit b8ced02d341a6b4c696a52fffe5bb339e7867104
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 23:42:17 2020 -0500

    Fixed Flake8 linting issues

commit 82770a7bc8be31024948188ccb58ee2809889c6c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 23:41:57 2020 -0500

    Fixed Ansible linting issue

commit c47ee7b413bc56ba243e0960acf71404cffc8eb9
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 23:33:40 2020 -0500

    Added new Molecule tests, etc. from new structure

commit 625e35a980142af7c3ef17e90c8dbea0e3245da3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 23:32:43 2020 -0500

    Updated files, etc. after new structure

commit c7edbc155ad11503b5100fadb988d68383a22f7c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Feb 22 22:46:21 2020 -0500

    Deleted old tests, etc. not needed

commit 571bf2e7267ad669e0aed47b789684795f24246d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 23 00:34:47 2018 -0500

    Disabled Debian as it is failing and needs to be investigated

commit 38644cd1fd295f976a65f883ce3acd13385c56cb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Dec 23 00:26:51 2018 -0500

    First commit of refactoring
    
    Cleaned up code based on Ansible lint and YAML lint
    Implemented updated Travis CI testing

commit 71430d317801634e801d6f7f4607741232de7a19
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 30 19:27:35 2018 -0400

    Added Ubuntu 18.04 supported

commit 2ee7f80d55592460ca3f3789b5a488a536d1e17a
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 30 19:27:14 2018 -0400

    Disabled all distros other than Ubuntu as this role is only supported

commit 36a348fab0a2e551357d28d9d46df117fd5c3e10
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 30 18:44:56 2018 -0400

    Skipping task check for ansible-lint as this task is required.

commit eecc7dfc12d682163fdadc2c9c86b4e632183352
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Mon Apr 30 17:16:45 2018 -0400

    Implemented new Travis-CI testing

commit b248c768dccad010690ec88d9670f25e1d308a7e
Author: Alexander Pinnecke <alexander.pinnecke@googlemail.com>
Date:   Mon Dec 18 16:18:06 2017 +0100

    iRemove protocol when using plain tcp load balancing, fixes #1

commit 2455fbf8c8c427379c8e3850e4427345db4ef538
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 14 15:59:28 2017 -0400

    Comment Out Default SSL Info
    
    Commented out the default SSL info in order to clean up and make the
    defaults cleaner.
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 68cc9b51ed4dd40d3219054b6fb930af9a58190c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 13 22:43:54 2017 -0400

    Add HA SSL Cert Sync Ability
    
    Added HA setup options which includes the ability to define an HA
    primary node which will generate SSL certs and those will be synced to
    the other load balancers in the HA setup. This will allow for SSL
    termination using the same keys across all load balancer nodes.
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit fe16bc45e7a47ce7dd68d5363291670a63c7bd8f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 13 20:35:03 2017 -0400

    Updated Galaxy/Repo Info
    
    Signed-off-by: Larry Smith Jr <mrlesmithjr@gmail.com>

commit 7802c7bc893bff8a523155cb70f4c2e2f8631a9b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Jul 13 20:30:05 2017 -0400

    first commit
