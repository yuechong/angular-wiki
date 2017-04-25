# angular-wiki

angular $controller

#$controller http://jasonwatmore.com/post/2014/03/25/angularjs-a-better-way-to-implement-a-base-controller
demo in use ng-controller as vm
angular.extend(vm,$controller('CommonController',{vm:vm}))


#DELAYING THE $DIGEST() CYCLE IN ANGULARJS https://www.aaron-gray.com/delaying-the-digest-cycle-in-angularjs/
<input ng-model="user.name" ng-model-options="{ debounce: 150 }" />
