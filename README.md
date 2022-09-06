# Assignement of Test Vagrant
Project Name - AssignementTestvagrant
Folders      - 1. src/main/java - it includes 1)Testbaseclass in Testvagrantpom package 2)imdbpage and Wikiwebpage are pom class are also in Testvagrantpom package(Where Web element initiated using pagefactory).
               2. src/test/java - This folder cincludes main test case named as Datencountryvalidate test class in package testvagranttest
Aim          - To compare Date of release and country of origin for The movie Pushpa in IMDB and WIKI, where if date of release or country of origin not matches test case should fail.
Execution Process:
1. Initially Testbaseclass are created for Base of Test class, after that To initialise driver and launching URL in testcase DatenCountryvalidate, POM class are created &  Testbaseclass is inherited by Datencountryvlaidate test class.
2. Two tests are there in testcase 1. releaseDatePushpa
                                   2.originCountryOfPushpa

3. After application of Assertion are use here so, in this test case releaseDatePushpa release dates are not matches so test case are fails due to assertionErrorException and in test case originCountryOfPushpa Country of origin matches so test case are pass.
4. To see reult you have to run CompareDatenCountryForPushpa as TestNG suite.
# Assignementtestvagrant
# Assignementtestvagrant
