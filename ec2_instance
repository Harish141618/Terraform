provider "aws" {
region="us-east-1"
}
resource "aws_instance" "one" {
tags = {
Name = "myinstance"
}
ami="ami-0953476d60561c955"
instance_type="t2.micro"
count=1
}
