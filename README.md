# terraform-as-vpcoctober

module "vpc" {
    source = ""
    version = "0.0.2"
    region = "us-east-2"
    region = "us-east-2"
    vpc_cidr = "10.0.0.0/16"
    subnet1_cidr = "10.0.1.0/24"
    subnet2_cidr = "10.0.2.0/24"
    subnet3_cidr = "10.0.3.0/24"
    vpc_name = "kaizen"
    instance_type = "t2.micro"
    key_name = "hello"
    type = true
}