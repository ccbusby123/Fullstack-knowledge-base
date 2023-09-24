//Type Inference

let course = 'React - The Complete Guide';

course = 12341;

This will cause an error even though a type is not assigned. TS used a powerful feature of Type Inference. By default TS will try to infer as many types as possible. It tries to learn which types are learned where without me explicitly defining them.