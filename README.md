# recrutement
La gestion de recrutement des employés dans une banque
# GESTION DE COMPTE
# coding :utf-8
class banque :
 
   def __init__(self):
       
          self.nom=""
          self.prenom=""
          self.numeroCompte=""
          self.balance= 0
          self.lieuVersement= "B.A.C"
          
          def_set_lieuVersement(self, nouvaeuVersement)
class Guichetier(banque):
    
    def __init__(self):
        """On créé des variables"""
        self.nom =""
        self.poste =""
        
            control_1 = Guichetier()
            control_1.nom = "abdel"
            control_1.poste = "num3"

           print(control_1.nom)
           print(control_1.poste)  

    
class controleurs(banque):
        
        def __init__(self, nom, matricule):
            
            self.nom= nom
            self.matricule= matricule
            return "controleurs{0}, matricule{1}".format(self.nom, self.matricule)
               
               controleurs=controleurs("Ben", 18A181FS)
               banque__init__(self, nom)
               self.matricule= matricule
               
 class gestionnaires(banque):
        def __init__(self, nom, tel, email):
            
            self.nom=nom
            self.tel=tel
            self.email=email
            return "gestion{0}, numeroTelephone{1}, compteEmail{2}".format(self.nom, self.tel, self.email)
        
           gestionnaires=gestionnaires("Ben", 691593194, benbachirou@gmail.com)
           banque__init__(self, nom, email)
           self.tel=tel
           
           
 class Client:
    
    ef __init__(self):
        """ On créé des variables d'un client"""
                 self.nom =""
                 self.prenom =""
                 self.adresse = ""
                 self.compte =""
        
                 client_x = Client()
                 client_x.nom= "ABD"
                 client_x.prenom= "AB"
                 client_x.adresse= "@abd"
                 client_x.compte= "expresse"
                 print(client_x.nom)
                 print(client_x.prenom)
                 print(client_x.adresse)
                 print(client_x.compte)
