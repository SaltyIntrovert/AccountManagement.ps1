Scripts are being with Power Automate, using both Web and Desktop flows <br/>
>>> Power Automate configuration not available <br/>

  >"%*%" are used as variables that Power Automate feeds into the Powershell script <br/>

  >The Web flow is started when a webhook or MS Form request is received<br/>
>> -Which starts the desktop flow, after creating a few accounts it will send the information back to the Web flow <br/>
>> -Web flow sends one email with account information to managers and needed HR reps <br/>
>>>  -2nd email creates a ticket to add access that couldn't be automated based on our lack of access to some applications <br/>

Sensative information has been swapped out with *******

# PAW = Power Automate Web
# PAD = Power Automate Desktop
