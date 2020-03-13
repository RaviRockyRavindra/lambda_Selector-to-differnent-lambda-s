# @Author Ravindra sai konna

<html>
<img src="https://rockymore.s3.ap-south-1.amazonaws.com/dynamodb_lambda.jpg ">
</html>

# boto3 aws sdk for python

# lambda_Selector-to-differnent-lambda-s

lambda_selector to different lambdas here lambda selector will decide where and what to invoke . All we need to work on passing the exact parameters in addition lambda name as source and find more by looking over the architecture

In the above architecture the complete functionality of lambda depends on the parameter passing (source=?). For the sake of practise attached the dynamodb and storing the values over there.Here my 4 lambdas working on different operations (CRUD) Create, Read, Update, Delete moreover in the time of using all we need to append one more param called source=? (ex:source= lambda1).lambda_selector will pull the param and based on the condition that will route to the proper function.
