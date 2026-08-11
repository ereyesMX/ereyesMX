<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <style>
        /* Estilos Modernos para el perfil */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0d1117; /* Fondo oscuro estilo GitHub Night Mode */
            color: #c9d1d9;
            margin: 0;
            padding: 2rem;
        }

        .container {
            max-width: 800px;
            background-color: #161b22;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.5);
            padding: 3rem;
        }

        /* Banner con fondo */
        .banner {
            height: 180px;
            width: 100%;
            background-color: #0d1117; 
            border-radius: 4px;
            margin-bottom: -3rem; /* Efecto de superposición moderna */
            position: relative;
            overflow: hidden;
        }

        .banner img {
             width: 100%;
             height: 125%; /* Estirar para cubrir altura completa + bordes redondeados del contenedor */
             object-fit: cover; 
             opacity: 0.6; /* Un poco transparente sobre el dark mode */
        }

        .profile-header { text-align: center; margin-bottom: 2rem;}
        
        h1, h2, h3 { color: #ffffff; font-weight: bold; }
        
        .about-section { background: rgba(0,0,0,0.2); padding: 1.5rem; border-radius: 8px; margin-bottom: 2rem;}

        /* Grid de Skills */
        .skills-grid {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            padding: 2rem 0;
            border-top: 1px solid #30363d;
            margin-bottom: 3rem; 
        }

        .skill-category { text-align: center; width: 45%; min-width: 280px;}
        .skills-list { display: flex; justify-content: center; gap: 15px; align-items: center; padding-top: 10px;}

        /* Nuevas secciones del futuro */
        .future-tech, .projects-preview { margin-bottom: 2rem; }
        
        footer { font-size: 0.9em; color: #8b949e; text-align: center;}

    </style>
</head>
<body>

<div class="container">
    
    <!-- BANNER CON FONDO -->
    <div class="banner" style="--img-url: url('https://images.unsplash.com/photo-1507723984695-baafac6f90b5?q=80&w=2070&auto=format&fit=crop'); background-image: var(--img-url);">
    </div>

    <!-- HEADER / NOMBRE -->
    <header class="profile-header" style="margin-top:-4rem; position:relative;">
        <h1>Juan Pérez</h1>
        <p><em>Diseñador de Bases de Datos & Arquitecto Backend Senior</em></p>
        
        <!-- Sección 3: Acerca de mí -->
        <div class="about-section">
            <strong>Sobre Mí:</strong> 
            Ingeniero especializado en el desarrollo de sistemas escalables y la arquitectura robusta de datos. Mi pasión radica en diseñar ecosistemas donde SQL no es solo un lenguaje, sino una herramienta crítica para optimizar procesos empresariales complejos a nivel global. Con más de 5 años fusionando lógica backend con eficiencia algorítmica, construyo soluciones que soportan grandes volúmenes de transacciones sin sacrificar la velocidad ni el rendimiento.
        </div>

        <!-- Sección: Skills (Badges Oficiales) -->
        <h2>Tecnologías & Habilidades</h2>
        
        <div class="skills-grid">
            
            <!-- Backend Core Java -->
            <div class="skill-category" style="width: 100%; text-align:center;">
                <strong>Núcleo de Desarrollo (Backend)</strong><br>
                <div class="skills-list">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="32" height="32"><br/><small style="color:#aaa;">Java</small>
                    <img src="https://cdns.iconscout.com/illustration/premium/thumb/spring-boot-4186975-3084359.png?f=webp&h=64&w=64" width="32"><br/><small style="color:#aaa;">Spring Boot</small>
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="32" height="32"><br/><small style="color:#aaa;">JavaScript / JS</small>
                </div>

            <!-- Frontend -->
             <div class="skill-category" style="width: 100%; text-align:center; margin-top: 5px;">
                 <strong>User Experience (Frontend)</strong><br>
                 <div class="skills-list">
                     <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="32" height="32"><br/><small style="color:#aaa;">React</small>
                     <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="32" height="32"><br/><small style="color:#aaa;">TypeScript</small>
                 </div>

            <!-- Bases de Datos -->
             <div class="skill-category" style="width: 100%; text-align:center; margin-top: 5px;">
                <strong>Data & Persistencia (Especialidad)</strong><br>
                <div class="skills-list">
                    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/oracle/oracle-original.svg" width="32"><br/><small style="color:#aaa;">Oracle PL/SQL</small>
                     <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-plain-wordmark.svg" width="30"><br/><small style="color:#aaa;">PostgreSQL</small>
                </div>

            <!-- Nube & Modernidad -->
             <div class="skill-category" style="width: 100%; text-align:center; margin-top: 5px;">
                <strong>Ingeniería & DevOps (Modern Stack)</strong><br>
                 <div class="skills-list">
                     <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="30"><br/><small style="color:#aaa;">Git</small>
                      <img src="https://cdns.iconscout.com/illustration/premium/thumb/docker-4682197-2514217.png?f=webp&h=64&w=64" width="30"><br/><small style="color:#aaa;">Docker</small>
                      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/oracle-cloud-infrastructure/oracle-cloud-infrastructure-original.svg" width="25"><br/><small style="color:#aaa;">OCI Cloud</small>
                </div>

            <!-- Nuevas secciones inventadas para 2026 -->
             <div class="skill-category future-tech">
                 <strong>NUEVA ESPECIALIDAD: AI Integration (Hipermedia)</strong><br>
                 Utilizando LLMs y Agentes de IA en flujos transaccionales. Diseño prompts SQL generativos e integración RAG para bases de datos vectoriales.
             </div>

        </div> <!-- Fin Skills -->


         <h3>Mis Proyectos Destacados</h3>
         
        <p style="margin-top: 0;">🚀 **Oracle Financials Core:** Migración masiva a arquitectura microservicios en Oracle APEX, reduciendo tiempos de respuesta en un 40%.</p>

    </div> <!-- Fin Skills -->


     <!-- Contacto -->
    <footer>
        <h3>Contacto</h3>
        
        📧 juan.perez@gmail.com<br><br>
        📱 +52 55-4532-8511<br><br>
        💼 Disponible para proyectos freelance y consultoría de arquitectura Oracle & Spring Boot.

    </footer>

</div>
</body>
</html>
