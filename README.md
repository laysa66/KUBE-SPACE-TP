# 🚀 OPÉRATION KUBE-SPACE : MISSION DE SAUVETAGE

> **Durée** : 55 min | **Niveau** : Débutant ⭐ | **Créateurs** : Lysa Matmar & Omar Samy Ahmed Hussein (Polytech Montpellier)

## 🎯 Contexte de la Mission

La station spatiale **K8S-Alpha** dérive dans l'espace. Les anciens systèmes sont tombés en panne. Vous êtes envoyé(e) en urgence pour **redémarrer les moteurs de contrôle** en utilisant **Kubernetes** pour orchestrer les systèmes critiques.

**Statut** : 🚨 **URGENT**  
**Lieu** : Station Spatiale K8S-Alpha  
**Votre rôle** : Ingénieur(e) DevOps  
**Équipement** : Minikube, Kubectl et le courage ✊



## 🛠️ Prérequis

### Installation requise

Assurez-vous d'avoir installé les outils suivants :

```bash
# Vérifier Minikube
minikube version

# Vérifier Kubectl
kubectl version --client
```

**Besoin d'installer ?** Consultez la section [Aide Rapide](#-aide-rapide) en fin de document.

---

## 📚 Architecture du TP

### Phase 1️⃣ : Redémarrage d'Urgence (15 min)

Déployez une application web 2048 dans un **Pod** et exposez-la via un **Service** NodePort.

**Concepts couverts** :
- Structure YAML d'un Pod
- Labels et selectors
- Types de Services (ClusterIP, NodePort, LoadBalancer)
- Communication Pod ↔ Service

**Livrables** :
- `pod-moteur.yaml` - Configuration du Pod
- `service-moteur.yaml` - Configuration du Service

---

### Phase 2️⃣ : Systèmes Redondants et Résilience (30 min)

Transformez le Pod isolé en **Deployment** avec 3 replicas et testez le self-healing automatique.

**Concepts couverts** :
- Structure YAML d'un Deployment
- Réplication automatique
- Self-healing (recréation auto de Pods)
- Scaling dynamique

**Livrables** :
- `deployment-moteur.yaml` - Configuration du Deployment
- Tests de résilience

---

## 📬 Feedback

Avez-vous des retours sur ce TP ?  
**[Répondez au questionnaire](https://forms.gle/rcy6G8whS3NAyPve7)**

---

## 📄 Auteurs

- **Lysa Matmar** - Polytech Montpellier
- **Omar Samy Ahmed Hussein** - Polytech Montpellier

---

## 📖 Références

- [Documentation Kubernetes Officielle](https://kubernetes.io/docs/)
- [Minikube Setup](https://minikube.sigs.k8s.io/)
- [Kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)

---

**Licence** : Libre d'usage éducatif
