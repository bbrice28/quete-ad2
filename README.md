# quete-ad2

### 1. Créer une Unité d'Organisation `Wilders_students`

1. Ouvrez la console de gestion Centre d'Administration Active Directory.
2. Dans l'arborescence de la console, cliquez avec le bouton droit sur le domaine `wilders.lan` et sélectionnez **New** > **Organizational Unit**.
3. Dans la fenêtre qui s'ouvre, nommez l'OU `Wilders_students`.
4. Cliquez sur **OK** pour créer l'OU.

### 2. Créer un Groupe d'utilisateurs `Students`

1. Toujours dans la consoleCentre d'Administration Active Directory, naviguez jusqu'à l'OU `Wilders_students` que vous venez de créer.
2. Cliquez avec le bouton droit sur `Wilders_students`, puis sélectionnez **New** > **Group**.
3. Dans la fenêtre **New Object - Group**, nommez le groupe `Students`.
4. Sélectionnez le scope du groupe (par exemple, **Global**) et le type de groupe (par exemple, **Security**).
5. Cliquez sur **OK** pour créer le groupe.

### 3. Créer un Utilisateur au sein du Groupe `Students`

1. Dans la console ADUC, naviguez à nouveau jusqu'à l'OU `Wilders_students`.
2. Cliquez avec le bouton droit sur `Wilders_students`, puis sélectionnez **New** > **User**.
3. Dans la fenêtre **New Object - User**, remplissez les champs nécessaires pour créer l'utilisateur. Par exemple :
   - nom
   - prénom
   - mdp
4. Cliquez sur **OK**.
5. Pour ajouter cet utilisateur au groupe `Students`, faites un clic droit sur l'utilisateur nouvellement créé, sélectionnez **Add to a group**.
6. Tapez `Students` dans la boîte de dialogue et cliquez sur **Check Names** pour vérifier le groupe.
7. Cliquez sur **OK** pour ajouter l'utilisateur au groupe `Students`.
