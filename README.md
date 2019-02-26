<h1 align="center"> Metode de dezvoltare software </h1>

<h3>Grupele 353 si 354 -Tanase Denisa - denisatanase@gmail.com </h3>


<h3>Proiect - 3 puncte</h3>
<a href="https://docs.google.com/spreadsheets/d/1amgYh-Q6Iunb-her7gZtfMPpSmxns3Ks5wXu2-VLEN8/edit?usp=sharing">Echipe</a>
<h4>Cerințe:</h4>
<ol>
  <li>
    (1p) Aplicație MVC - folosind Entity Framework (C#) / Hibernate (Java) / ....
    <br>
    Trebuie să prezentați tema proiectului, specificațiile acestuia și detaliile de implementare.
  </li>
  <li>
    (1.5p) Servicii - fiecare membru al echipei trebuie să realizeze un serviciu care să funcționeze independent (folosind orice limbaj de programare). Acesta va rula local, dar și în Cloud.
    <br>
    Aplicația MVC trebuie modificată pentru a consuma aceste servicii realizate.
  </li>
  <li>
    (0.5p) Dificultatea proiectului. Se acordă cele 0.5p în funcție de dificultatea proiectului realizat.
  </li>
</ol>
Deadlines: 
<ul>
  <li>Săptămâna 5-6 - idei + specificații.</li>
  <li>Săptămâna 9-10 - MVC + prezentare.</li>
  <li>Săptămâna 11-12 - 1 serviciu funcțional - deploy Cloud.</li>
  <li>Săptămâna 13-14 - prezentare finală.</li>
</ul>
Prezentarile intermediare si finale au loc in cadrul seminarului.
<br>

<h3>Prezenta si Activitate Laborator - 1 punct</h3>
<a href="https://docs.google.com/spreadsheets/d/1PomMMi2i74YGPDtbK-BBCOomrNxRfWrVK7qwsRqNfgE/edit?usp=sharing">Prezenta</a>


<h3> Bonus - Documentatie proiect - 1 punct</h3>
<a href="https://docs.google.com/document/d/1JU702EZb6_U6X5u_2mjBPM_SfmAbbVh7FW-hktA-q2A/edit?usp=sharing">Continut documentatie</a>

<br>
<h3>Laborator</h3>
<h3>MVC - Entity Framework</h3>
<a href="https://drive.google.com/open?id=1PQiNpw6a8_aB5MhDIzPYmEMAom_LBfRJ">EF Tutorial</a>
<br>
<h5>Eroare la conexiunea cu baza de date in proiectul de MVC<h5>
In Web config, trebuie modificat String-ul de conexiune:
<br>
connectionString="Data Source=(LocalDb)\MSSQLLocalDB;Initial Catalog=ContosoUniversity1;Integrated Security=SSPI;"
<br>
Daca Controllerul a fost creat cu Students, trebuie modificata si ruta:
<br>
@Html.ActionLink("Students", "Index", "Students")
<br>
<br>
<a href="https://goo.gl/forms/F5XycONQTcuftXiD3">Sugestii/reclamatii</a>

