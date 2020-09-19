<!doctype html>
<html>
    <head>
        <title>autocomplete search with AngularJS and PHP</title>

        <link href='style.css' rel='stylesheet' type='text/css'>
        <script src="angular.min.js"></script>

        <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
        
    </head>
    <body ng-app='myapp'>


        <div class='container' ng-controller="fetchCtrl" ng-click='containerClicked();' >
        
           <input type='text' ng-keyup='fetchUsers()' ng-click='searchboxClicked($event);' ng-model='searchText' placeholder='Enter text'><br>
            <ul id='searchResult' >
                <li ng-click='setValue($index,$event)' ng-repeat="result in searchResult" >
                  {{ result.name }}
                </li>
            </ul>  
        </div>
        
        <!-- Script -->
        <script>
        var fetch = angular.module('myapp', []);

        fetch.controller('fetchCtrl', ['$scope', '$http', function ($scope, $http) {
            
            // Fetch data
            $scope.fetchUsers = function(){
                
                var searchText_len = $scope.searchText.trim().length;

                // Check search text length
                if(searchText_len > 0){
                    $http({
                    method: 'post',
                    url: 'getData.php',
                    data: {searchText:$scope.searchText}
                    }).then(function successCallback(response) {
                        $scope.searchResult = response.data;
                    });
                }else{
                    $scope.searchResult = {};
                }
                
            }

            // Set value to search box
            $scope.setValue = function(index,$event){
                $scope.searchText = $scope.searchResult[index].name;
                $scope.searchResult = {};
                $event.stopPropagation();
            }

            $scope.searchboxClicked = function($event){
                $event.stopPropagation();
            }

            $scope.containerClicked = function(){
                $scope.searchResult = {};
            }
            
        }]);

        </script>
        
    </body>

</html>


        