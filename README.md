# jsHigherOrder

//forEach

arr.forEach(arrItem => action( arrItem ))

//filter: insert to a new array only wanted items from old array

let filtered_arr = arr.filter( arrItem => condition to add arrItem to filtered_arr )

//map: do action on each array item

let mapped_arr = arr.map( arrItem => return info about arrItem )

//sort: sort array in wanted order

let sorted_arr = arr.sort( (arrItem1, arrItem2) => return 1 if arrItem1 > arrItem2 else -1 )

//reduce: get value from all items in arr

let res = arr.reduce( (res, arrItem) => res.action(arrItem), initial value of res )

#v5
