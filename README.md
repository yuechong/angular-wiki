# angular-wiki

angular $controller
demo in use ng-controller as vm
angular.extend(vm,$controller('CommonController',{vm:vm}))


#DELAYING THE $DIGEST() CYCLE IN ANGULARJS https://www.aaron-gray.com/delaying-the-digest-cycle-in-angularjs/
<input ng-model="user.name" ng-model-options="{ debounce: 150 }" />
