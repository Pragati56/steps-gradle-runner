## Changelog (Current version: 1.7.8)

-----------------

### 1.7.8 (2017 Oct 20)

* [e88d1da] Prepare for 1.7.8
* [f55bce8] Test apk export (#47)

### 1.7.7 (2017 Sep 05)

* [1cf8dea] Prepare for 1.7.7
* [ba03ffb] Dependency file generation fix (#44) (#45)

### 1.7.6 (2017 Jul 28)

* [3b0f6af] Prepare for 1.7.6
* [7eebcd1] Lockfilecontentfix (#42)

### 1.7.5 (2017 Jul 28)

* [dfd7115] Prepare for 1.7.5

### 1.7.4 (2017 Jul 28)

* [4531cec] Prepare for 1.7.4
* [3a85104] Lockfile generation fix (#41)

### 1.7.3 (2017 Jul 21)

* [90e8141] Prepare for 1.7.3
* [e8a68dc] Dependencies with lockfile (#40)

### 1.7.2 (2017 Jul 14)

* [d34d802] prepare for 1.7.2
* [68e69e3] Retry gradle command (#39)

### 1.7.1 (2017 Jun 26)

* [17cd35e] Prepare for 1.7.1
* [a2a7925] godeps-update, added cacheLevel input (#38)

### 1.7.0 (2017 Jun 08)

* [5790862] prepare for 1.7.0
* [07dccbd] APK_LIST fix
* [6e088e2] input grouping and reordering (#35)
* [4d13e02] bitrise.yml updates (#36)
* [60dcc1e] added ~/.m2 dir include
* [4d0448b] export apk list (#34)

### 1.6.3 (2017 May 31)

* [4ff25ae] Prepare for 1.6.3
* [3f8b9f7] updated cache ignore paths (#33)

### 1.6.2 (2017 May 30)

* [262c786] Prepare for 1.6.2
* [3f2b509] sample forked and url changed (#32)

### 1.6.1 (2017 May 30)

* [fc69adb] Prepare for 1.6.1
* [792b2a6] switch to SOURCE_DIR search (#31)

### 1.6.0 (2017 May 26)

* [f45de0a] Prepare for 1.6.0
* [457d161] Added built-in cache collection (#30)

### 1.5.6 (2017 May 04)

* [527ec0f] Prepare for 1.5.6

### 1.5.5 (2017 May 04)

* [4f31d28] Prepare for 1.5.5
* [4f87888] Gradle build file made optional (#28)
* [12d9170] godeps-update
* [f5d87a9] Remove cmdex, add command (#27)

### 1.5.4 (2017 Jan 30)

* [e77a176] prepare for 1.5.4
* [56c5620] filter input clarifications (#24)

### 1.5.3 (2017 Jan 26)

* [a9ada0c] prepare for 1.5.3
* [00c3bc4] Changed find option `-name` to `-path` in mapping.txt include/exclude filters (#23)
* [a106b31] updates

### 1.5.2 (2016 Sep 27)

* [103870d] prepare for 1.5.2
* [f339afc] find fix (#19)

### 1.5.1 (2016 Sep 16)

* [b8b89c6] prepare for 1.5.1
* [54eadf7] shell quote gradle tasks (#16)

### 1.5.0 (2016 Sep 14)

* [71e87eb] prepare for 1.5.0
* [54e1eaf] Go (#14)
* [a7accb7] share v1.4.1

### 1.4.1 (2016 Aug 17)

* [d7dccea] Feature/remove workdir (#11)
* [5114a08] share v1.4.0

### 1.4.0 (2016 Aug 17)

* [2efa724] Merge pull request #10 from bitrise-io/feature/gradlew-required
* [3e3f363] updated README
* [d771c28] gradlew path is now required
* [a7fc4cc] revisions in bitrise.yml, for easier testing
* [d69f4ec] new test repo(s)
* [3300ea2] make sure commit nor tag nor pr id is set

### 1.3.1 (2016 Feb 10)

* [271ae05] STEP_GIT_VERION_TAG_TO_SHARE: 1.3.1
* [8296d4b] Merge pull request #9 from godrei/mapping_filter
* [5871c7d] Typo fix, removed default values
* [33df200] filter mapping files

### 1.3.0 (2016 Feb 09)

* [889fabf] STEP_GIT_VERION_TAG_TO_SHARE: 1.3.0
* [856b65f] Merge pull request #8 from godrei/gradlew_permission
* [6e0527d] search for mapping.txt
* [270b6ef] docker-compose.yml deprecation fix
* [12c8a9f] Merge pull request #7 from godrei/gradlew_permission
* [826d7ab] PR fix
* [8b5e0a0] gradlew: add executable permission
* [aea2118] STEP_GIT_VERION_TAG_TO_SHARE: 1.2.0

### 1.2.0 (2015 Dec 16)

* [1a37056] NEW : Step now generates an `$BITRISE_APK_PATH` output
* [02eabe3] share 1.1.1

### 1.1.1 (2015 Nov 24)

* [0b1ebf7] gradle options input, to specify debug flags easily; logging: printing the build configuration; testing: gradlew path

### 1.1.0 (2015 Nov 19)

* [5ea3a71] v1.1.0
* [b0b7627] option to specify `gradlew` path as an ENV (default value) ; default exclude filter for `unaligned` APKs ; bit of logging improvements
* [b3551f2] `share-this-step` workflow

### 1.0.0 (2015 Nov 11)

* [5f35ecc] `BITRISE_DEPLOY_DIR` env note
* [197ad79] step.yml revision
* [e02710d] `workdir` #fix ; detecting `gradlew` and using it if available ; docker-compose based test & bitrise.yml revision for easier testing
* [ac9f6ee] Merge pull request #3 from selcukbulca/master
* [f4ef72f] Add filter for excluding apk files
* [45f1269] additional inputs
* [dc01bba] gradle_file input

### 0.9.3 (2015 Oct 31)

* [ee2650b] code cleared up a bit

### 0.9.2 (2015 Oct 31)

* [3e96ed6] Copies all or the specified APKs to $BITRISE_DEPLOY_DIR
* [5d9c4f0] support for separate gradle_file

### 0.9.1 (2015 Oct 29)

* [cc24394] yml updated
* [0e3e0bc] yml updates

-----------------

Updated: 2017 Oct 20