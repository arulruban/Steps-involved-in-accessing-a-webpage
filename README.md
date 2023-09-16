# Steps-involved-in-accessing-a-webpage
step 1: The URL(unifom resource locator) of the requiired webpage should be entered in the browser. example of browsers(chrome,firefox,microsoft edge) and example of URL(www.gmail.com).
step 2: The URL request will go to the DNS resolver inorder to fetch the ip address of the requested webpage.
step 3: The request will be sent to the root server from DNS resolver which will determine the to which root server the webpage belongs using the domani name . The ip address of the root server will be sent back to DNS resolver. Ex (.com, .org, .edu).
step 4: Then the request will move on to the TLD server which will use the domain name to determine the ip of the sever. Ex (gmail.com)
step 5: Then the request will move on to the authoritative server which will contain all the IP address of the webpage which will match the URL with the IP address and the IP address will be passed to the client machine which will load the requested webpage in the cleient machine.
NOTE: The main purpose of the DNS is to match the URL present and find the respective IP address.
