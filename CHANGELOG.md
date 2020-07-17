commit 0edc1feea7df5a95b891077d88d1d3abbfa28da4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 09:07:20 2020 -0400

    Added Apt cache_valid_time back

commit af327d2594b8dd2723abffe4b5406bc095a305f6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 09:07:01 2020 -0400

    Updated Python requirements

commit f433bed712a9f461dbb7bbbb991c653d5aa93c8e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 08:33:07 2020 -0400

    No winning here
    
    Regardless of which route we take with apt cache_valid_time, Molecule has issues

commit cce19d1433feae47ce10a74446d28880d3dc0244
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 08:14:40 2020 -0400

    Changing Apt Cache valid time
    
    For whatever reason cache is not updating as we are expecting

commit b896bde5857f54169e6980184b4ae0a02af01885
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Jul 17 08:04:28 2020 -0400

    Updated CI tests to latest

commit 324748bcffad155775bd64368e00c0bdedf10ac6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu May 7 22:55:41 2020 -0400

    Added APT cache update for Debian
    
    To ensure that our apt sources are updated in order to install packages.
    We needed to add this.

commit 65e9e8e7522ee9f1faa8560b3a6c9b8e2bbc608b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Feb 27 11:09:38 2020 -0500

    Added CHANGELOG

commit c16f90a48d177e3c649f6e458b5170d61f588d1f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Feb 27 11:07:37 2020 -0500

    Disabled all additional parameters for images
    
    - With the parameters that were set, various Python modules do not
    execute properly. Have tested numerous things and it came down to this.

commit c45f656ea0dc432de5c428cdf9422791f60614ab
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sun Feb 23 00:36:55 2020 -0500

    Added rediscover facts task
    
    - This should ensure that facts are rediscoverd to get Python interpreter if changed

commit 6e537a4e62dca0805d25d8870519fb9c8e544eeb
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 18:14:51 2020 -0500

    Changed names of tasks from pre-reqs

commit 1e360ce691e83c8ea25a1d89abe6efa83fb3aaaa
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Feb 21 17:38:02 2020 -0500

    first commit
