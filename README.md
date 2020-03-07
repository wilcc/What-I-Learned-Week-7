# What-I-Learned-Week-7

Function can be used by other function

sample

const call = function (funk){
  funk()
}

or can be multiple functions

const threeFuncs = function(funk1,funk2,funk3){

  return funk3(funk2(funk1()))
}

functions can also be used in dom manipulation
'make sure function is const and cannot be changed'

use addEventListener to set up a waiting change which will not be called until specific action or event has occur
example: 'click','dblclick','mouseenter','mouseout'

use setInterval to delay and reoccur in the specific time frame

use querySelectorAll to select all of the specific element and then loop through to make changes to all selected