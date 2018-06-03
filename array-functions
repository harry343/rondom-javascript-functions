/**
 *get arrays of items that do not exist in another array
 * 
 * @param {Array} getFrom array to get items from 
 * @param {Array} checkFrom array to check items from
 * @returns {Array} return arrays of non existing items
 * source https://stackoverflow.com/a/19957433/4273202
 */
function getNonExistingItems(getFrom, checkFrom) {

  var nonExistingItems = getFrom.filter(function (item) {

    return checkFrom.indexOf(item) < 0;
  });
  return nonExistingItems;
}

/*
example 
var oldSubscriptionsList = ['a', 'b', 'c', 'd', 'e'];

var newSubscriptionsList = ['b', 'c', 'd', 'f', 'g'];
var unsubscribed = getNonExistingItems(oldSubscriptionsList, newSubscriptionsList);
console.log(unsubscribed);
var newlySubscribed = getNonExistingItems(newSubscriptionsList, oldSubscriptionsList);
console.log(newlySubscribed);
*/
