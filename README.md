# project-1
# day-1
provider "aws" {
region = "us-east-1"
}
  resource "aws_instances" "new_ec-2"{
  ami = "ami-043cfcc8b0832d11a"
  instance_type = "t2.micro"
  subnets_id = "subnet-08ec7ed6ff2590096"
  key_name = "testkey-1"
  }
  
  
