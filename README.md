# [Snap Docker](https://github.com/snapcore/snapcraft/tree/master/docker)

* Build
  ```
  docker build --no-cache -f stable.Dockerfile --label cho2/snap --tag cho2/snap:stable --network host .
  ```

* Push 
  ```
  docker push cho2/snap:stable
  ```
