Node.js is a open source cross platform, back end JavaScript runtime environment that runs on the VB engine and execute JS code outside & Web browser

Node.js

MS Visual Studio Code

Playwright ku nama dependencies add pananum
  Inbuilt aavey namaku thevaiyana framewore related components irukku, simple commands kudutha pothum athuvey thevaiyana ellathaiyum build      panikum

  Nama MS VS Code bottom left la oru option irukkum atha click panna "Terminal" nu oru option ku poganum
  <img width="1365" height="642" alt="image" src="https://github.com/user-attachments/assets/328f1719-d435-4c1d-8ddc-b5460f022653" />

Java Script la nama enna develope panalum athu Node project tha

"npm init playwright" intha code kudukanum =  ithu PlayWright structure la oru project ah create pannum, project oda skeleton, dependencies ellamey ithuvey setup panni kuduthudum

"npm init playwright" intha command kudutha aprm PlayWright ah JavaScript ah nu kekum, namaku thevaiyanatha choose panikalam
Where to put your end-to-end tests? nu kekum default ah tests choose panikalam
Add a GitHub Actions workflow? (Y/n) . true
Install Playwright browsers (Can be done manually via 'npx playwright install')? (Y/n) . true or false
<img width="702" height="161" alt="image" src="https://github.com/user-attachments/assets/eaf30e3f-0efe-4eef-bf00-a25c5ceee4cb" />

Ithu la panitu enter kudutha Playwright project ah create panidum

Ipo sila vs code la irukura bug naala language ah athuvey choose panidichi na nama specefic ah direct command kudukalam
"npm init playwright -- --quit --lang js"

Playwright project successfull ah create aana aprm project explorer la enna enna add aachi nu pathukalam
<img width="302" height="248" alt="image" src="https://github.com/user-attachments/assets/7fc7a431-27e3-46f2-9b6d-c837aecba3df" />

Ithula "playwright.config.js" intha file tha romba important, because ithutha nama project ku Test runner for Project test Cases
"package.json" Node projects ku intha file default ah create aagidum (Playwright, CyPress, Protactor, Puppeter..) ithumaari JavaScript project ku lam intha file default ah create aagidum. Ithula Playwright oda dependencies information pathukalam

tests nu Project ulla oru folder ah create panidum athula "example.spec.js" nu oru file create aagi irukkum athu example test cases tha namakku useful ah irukkum

node_modules nu oru folder create aagi irukkum athula Playwright related jar files la irukkum
