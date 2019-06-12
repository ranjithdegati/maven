import boto3
region = 'your-current-region'
instances = ['your-instance-id-1', 'your-instance-id-2']

def lambda_handler(event, context):
    ec2 = boto3.client('ec2', region_name=region)
    ec2.start_instances(InstanceIds=instances)
    print 'started your instances: ' + str(instances)
