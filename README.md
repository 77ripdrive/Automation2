branch BDD_Cucumber with Cucumber realization
#branch master

run NOW
 mvn -Dbrowser=chrome -Dsurefire.suiteXmlFiles=src\test\resources\testng-smoke.xml -Denvironment=hC clean test
