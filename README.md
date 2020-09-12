# BlackboardExtension
BlackboardExtension Documentation
  
  
Blueprint:  
  SetValueAsStruct can set blackboard value.  
  GetValueAsStruct can get blackboard value.  
C++:  
 SetValue<UBlackboardKeyType_Struct>(KeyName, StructToBytePtr(Struct));  
 Struct = BytePtrToStruct<StructType>(GetValue<UBlackboardKeyType_Struct>(KeyName));  
