node {
   stage 'Stage 1'
   echo 'Hello World 1'
   stage 'Stage 2'
   echo 'Hello World 2'
   stage 'Stage 3'
   echo 'Hello World 3'
   sh '''#!/bin/bash

   sleep 2
   for x in {1..10} ; do
   echo $x
   done'''
}
