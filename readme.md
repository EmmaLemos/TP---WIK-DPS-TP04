TP n°4 : 
Capture du bon fonctionnement de l'application (cf : DEVOPS.PNG)
Le fichier du TP4 est celui qui s'appelle TP4.yaml

Pour démarrer le service créer : 
```kubectl port-forward service/echo-service 8080:8080```

Pour apply le fichier : 
```kubectl apply -f .\TP4.yaml```

Pour visualiser les différents pods :
```kubectl get pods -n ingress-nginx```

Pour delete le ingress : 
```kubectl delete ns ingress-nginx```


