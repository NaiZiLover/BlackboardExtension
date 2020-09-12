# BlackboardExtension
BlackboardExtension Documentation


Blueprint:
  SetValueAsStruct can set blackboard value.
  GetValueAsStruct can get blackboard value.
C++:
 SetValue<UBlackboardKeyType_Struct>(KeyName, StructToByte(Struct));
 Struct = ByteToStruct<StructType>(GetValue<UBlackboardKeyType_Struct>(KeyName));
