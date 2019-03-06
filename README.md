# Basics Commands useful GCloud

* To see what your default region and zone settings are

`$ gcloud config list`


* regions available list

`$ gcloud compute regions list`

* set region specific

`$ gcloud config set compute/region  southamerica-east1`

* list images available 

`$ gcloud compute images list`

* list instances 

`$ gcloud compute instances list`

* delete instance 

`$ gcloud compute instances delete my-instance2`

* check type machine 

`$gcloud compute machine-types list`

* create instance with basics attributes 

`$ gcloud compute instances create 'instance-2'
--machine-type "n1-standard-1" --image-project "debian-cloud" 
--image "debian-9-stretch-v20170918" --subnet "default" `

