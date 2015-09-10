Build & Run:

docker build --rm -t $USER/atomicrepo .

docker run --privileged -d -p 8000:8000 --name atomicrepo $USER/atomicrepo

docker exec -it atomicrepo bash 


Compose Tree:
cd fedora-atomic

git checkout f21

vi fedora-atomic-docker-host.json
