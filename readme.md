helm install demo ./dummy-app.tgz \
  --set route.enabled=true \
  --set route.host=my-demo.apps.cluster.example.com

  https://my-demo.apps.cluster.example.com