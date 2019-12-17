# Welcome !

### Vous trouverez ici des playbooks d'administration système pour les actions de base sur des environnements linux.

* banner.yml : playbook de déploiement de banner sur des serveurs
* copy_bash_profile.yml : playbook de déploiement de profiles pour certains utilisateurs su plusieurs serveurs
* deploy-vms.yml : <strong>[en phase de dev]</strong> playbook de création d'environnement sur vcenter.
* drupal_splunk.yml: deploiement et configuration rsyslog pour users spécifiques.
* fs_add.yml : playbook de création de FS à partir d'un fichier plat en indiquant le point de montage.
* fs_rm.yml : playbook de suppression de FS à partir d'un fichier plat en indiquant le FS à supprimer.
* nfs_server.yml : playbook de création d'un FS et d'export en vue d'en faire un point de montage NFS.
* limits.yml : playook modification/mise en place de limites soft et hard à la demande pour n'importe quel utilisateurs.
* ping.yml : playbook basique de ping d'un host distant.
* sudoers.yml : playbook de déploiement de configuration sudoers dans le sudoers.d/.
* update_server.yml : playbook d'update d'un serveur avec extra vars pour installer d'autres packages supplémentaires.
* user_add.yml : playbook de création de user à partir de template.
