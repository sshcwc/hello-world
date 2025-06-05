# hello-world
This repository is for practicing the GitHub Flow.variable "aws_region" {

# S3 Bucket creation
resource "aws_s3_bucket" "payroll_bucket" {
  bucket        = "${var.scenario_name}-payroll-${random_string.suffix.result}"
  force_destroy = true
}
