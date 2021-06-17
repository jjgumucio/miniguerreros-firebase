<script>
  // core components
  import AuthNavbar from "../components/Navbars/AuthNavbar.svelte";
  import Footer from "../components/Footers/Footer.svelte";
  import CardTeamMember from "../components/Cards/CardTeamMember.svelte";

  const newbornHand = "/assets/img/newborn-hand.jpg";
  const premature = "/assets/img/premature.jpg";

  const javiera = "/assets/img/javiera.png";
  const begona = "/assets/img/begona.png";
  const sofia = "/assets/img/sofia.png";
</script>

<div>
  <AuthNavbar />
  <main>
    <div
      class="relative pt-16 pb-32 flex content-center items-center justify-center min-h-screen-75"
    >
      <div
        class="absolute top-0 w-full h-full bg-center bg-cover"
        style="
          background-image: url(/assets/img/newborn-scale.jpg);
        "
      >
        <span id="blackOverlay" class="w-full h-full absolute opacity-75 bg-black" />
      </div>
      <div class="container relative mx-auto">
        <div class="items-center flex flex-wrap">
          <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
            <div class="pr-12">
              <h1 class="text-white font-semibold text-5xl">Estamos contigo!</h1>
              <br />
              <p class="mt-4 text-lg text-blueGray-200">
                En Mini Guerreros seremos un apoyo concreto a las necesidades de niños nacidos
                prematuros y sus familias. Desde Neonatología pasando por todas las etapas de su
                crecimiento y desarrollo.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div
        class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden h-70-px"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon class="text-blueGray-200 fill-current" points="2560 0 2560 100 0 100" />
        </svg>
      </div>
    </div>

    <section class="pb-20 bg-blueGray-200 -mt-24">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap">
          <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
            >
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400"
                >
                  <i class="fas fa-people-carry pilar-icon" />
                </div>
                <h6 class="text-xl font-semibold">Apoyo</h6>
                <p class="mt-2 mb-4 text-blueGray-500">
                  Brindamos apoyo psicológico, acompañamiento y orientación a padres o tutores
                </p>
              </div>
            </div>
          </div>

          <div class="w-full md:w-4/12 px-4 text-center">
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
            >
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-lightBlue-400"
                >
                  <i class="fas fa-universal-access big-icon" />
                </div>
                <h6 class="text-xl font-semibold">Acceso</h6>
                <p class="mt-2 mb-4 text-blueGray-500">
                  Atenciones en neuro-rehabilitación y otras prestaciones <br />
                  Acceso a beneficios y servicios
                </p>
              </div>
            </div>
          </div>

          <div class="pt-6 w-full md:w-4/12 px-4 text-center">
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg"
            >
              <div class="px-4 py-5 flex-auto">
                <div
                  class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-emerald-400"
                >
                  <i class="fas fa-users pilar-icon" />
                </div>
                <h6 class="text-xl font-semibold">Comunidad</h6>
                <p class="mt-2 mb-4 text-blueGray-500">
                  Queremos convertirnos en el espacio de encuentro para todos los niños prematuros y
                  sus familias en Chile.
                </p>
              </div>
            </div>
          </div>
        </div>

        <div class="flex flex-wrap items-center mt-32">
          <div class="w-full md:w-6/12 px-4 mr-auto ml-auto">
            <div
              class="text-blueGray-500 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
            >
              <i class="fas fa-book big-icon" />
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal">Historia de la fundación</h3>
            <p class="text-lg font-light leading-relaxed mt-4 mb-4 text-blueGray-600">
              La Fundación para prematuros <strong>Mini Guerreros</strong>, se funda en el año 2020
              en medio de la crisis sanitaria más grande que haya conocido el mundo con el fin de
              prestar ayuda a todos los niños prematuros que no podían tener acceso a sus terapias
              de rehabilitación.
            </p>
            <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-600">
              Su Fundadora, <strong>Javiera Hernández</strong>, madre de un prematuro extremo nacido
              en el año 2019 con solo 6 meses de gestación, vivió en carne propia la experiencia que
              significa caminar la vereda del nacimiento de un hijo en condiciones totalmente
              anormales. Felipe, su hijo, nació pesando 685 gramos y midiendo 32 centímetros lo que
              le otorgaba solo un 10% de probabilidades de sobrevivir.
            </p>

            <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-600">
              A raíz de esta historia, Javiera decide generar un grupo de apoyo en redes sociales
              llamado Mini Guerreros en donde conversaba con profesionales mediante lives y que
              permitía a los padres una comunicación directa con ellos para orientarlos en sus
              dudas.
            </p>

            <p class="text-lg font-light leading-relaxed mt-0 mb-4 text-blueGray-600">
              Debido a la necesidad de neuro-rehabilitación durante el año de pandemia, ya que los
              centros se mantenían cerrados, le solicita a las dos terapeutas de Felipe, Begoña
              Donoso y Sofía Escala que se unan al espacio en donde resuelven comenzar a impartir
              cursos para padres y enseñarles ejercicios para mover a sus hijos. Desde ahí las 3 se
              involucraron en la misión de ayudar a los prematuros.
            </p>

            <!--<a use:link href="/" class="font-bold text-blueGray-700 mt-8"> Leer mas... </a> -->
          </div>

          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
            <div
              class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg logo-indigo"
            >
              <img alt="..." src={newbornHand} class="w-full align-middle rounded-t-lg" />
              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon points="-30,95 583,95 583,65" class="logo-text-indigo fill-current" />
                </svg>
                <h4 class="text-xl font-bold text-white">Prematuro: Qué significa?</h4>
                <p class="text-md mt-2 text-white">
                  Un niño prematuro es aquel que nace antes de cumplir las 37 semanas de gestación.
                </p>
                <p class="text-md mt-2 text-white">
                  <strong>Dos tipos: <br />- Prematuro:</strong> Niños nacidos entre la semana 32 y
                  37 de edad gestacional.<br /><strong>- Prematuro Extremo:</strong> Niños nacidos antes
                  de cumplir la semana 32 de edad gestacional.
                </p>
              </blockquote>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="relative py-20">
      <div
        class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20 h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon class="text-white fill-current" points="2560 0 2560 100 0 100" />
        </svg>
      </div>

      <div class="container mx-auto px-4" id="services">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
            <img alt="..." class="max-w-full rounded-lg shadow-lg" src={premature} />
          </div>
          <div class="w-full md:w-5/12 ml-auto mr-auto px-4">
            <div class="md:pr-12">
              <div
                class="text-white p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full logo-indigo"
              >
                <i class="fas fa-baby text-xl big-icon" />
              </div>
              <h3 class="text-3xl font-semibold">Nuestros Servicios:</h3>
              <p class="mt-4 text-lg leading-relaxed text-blueGray-500">
                Te ofrecemos profesionales especializados en Prematuros que, analizando caso a caso,
                podrán establecer qué terapias son las más apropiadas para tu pequeñ@.
              </p>
              <ul class="list-none mt-6">
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xl font-semibold inline-block py-1 px-2 uppercase rounded-full text-white logo-indigo mr-3"
                      >
                        <i class="fas fa-crutch" />
                      </span>
                    </div>
                    <div>
                      <!-- <h3 class="text-blueGray-500">Rehabilitación</h3> -->
                      <p class="text-blueGray-500">
                        <strong>Rehabilitación:</strong><br />
                        Terapias con Kinesiólogos y Terapeutas Ocupacionales que lograrán que su retraso
                        motor se acorte y alcance sus hitos motores
                      </p>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xl font-semibold inline-block py-1 px-2 uppercase rounded-full text-white logo-indigo mr-3"
                      >
                        <i class="fas fa-user-friends" />
                      </span>
                    </div>
                    <div>
                      <!-- <h4 class="text-blueGray-500">Amazing page examples</h4> -->
                      <p class="text-blueGray-500">
                        <strong>Familia:</strong><br />
                        Proximamente contaremos con acompañamiento psicológico para cualquier proceso
                        que tú como mamá o papá necesites durante el crecimiento de tu hija o hijo.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="py-2">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="text-xl font-semibold inline-block py-1 px-2 uppercase rounded-full text-white logo-indigo mr-3"
                      >
                        <i class="far fa-surprise pilar-icon" style="padding-top: 5px;" />
                      </span>
                    </div>
                    <div>
                      <!-- <h4 class="text-blueGray-500">Dynamic components</h4> -->
                      <p class="text-blueGray-500">
                        <strong>Beneficios:</strong><br />
                        Aquí encontrarán diferentes productos y servicios relacionados con nuestros niños
                        y que siendo parte de la Fundación podrás acceder a descuentos y convenios especiales.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="pt-20 pb-48">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center text-center mb-24">
          <div class="w-full lg:w-6/12 px-4">
            <h2 class="text-4xl font-semibold">Nuetro equipo</h2>
            <p class="text-lg leading-relaxed m-4 text-blueGray-500">
              Contamos con profesionales de primer nivel para ayudarte con todas las necesidades y
              en todas las etapas
            </p>
          </div>
        </div>
        <div class="flex flex-wrap justify-center">
          <CardTeamMember
            name="Javiera Hernández"
            imgSrc={javiera}
            description="Madre de prematuro Periodista y Comunicadora Social. Administradora Pública (proc).<br /> Directora Fundadora"
          />
          <CardTeamMember
            name="M. Begoña Donoso"
            imgSrc={begona}
            description="Kinesióloga y especialista en seguiento del prematuro <br /> CoFundadora"
          />
          <CardTeamMember
            name="Sofía Escala"
            imgSrc={sofia}
            description="Kinesióloga y terapeuta Bobath <br/> CoFundadora"
          />
        </div>
      </div>
    </section>

    <section class="pb-20 relative block bg-blueGray-800">
      <div
        class="bottom-auto top-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden -mt-20 h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon class="text-blueGray-800 fill-current" points="2560 0 2560 100 0 100" />
        </svg>
      </div>

      <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
        <div class="flex flex-wrap text-center justify-center">
          <div class="w-full lg:w-6/12 px-4">
            <h2 class="text-4xl font-semibold text-white">Testimonios</h2>
            <p class="text-lg leading-relaxed mt-4 mb-4 text-blueGray-300">
              "La Fundación de Prematuros Mini Guerreros es nuestro mayor sueño, donde se conjuga el
              amor por lo que hacemos y la esperanza de contribuir a la felicidad de las familias
              que han tenido un niño prematuro."
            </p>
            <p class="text-lg leading-relaxed mt-4 mb-4 text-blueGray-400">
              Javiera Hernández - Fundadora
            </p>
          </div>
        </div>
        <!--
        <div class="flex flex-wrap mt-12 justify-center">
          <div class="w-full lg:w-3/12 px-4 text-center">
            <div
              class="text-blueGray-800 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
            >
              <i class="fas fa-medal text-xl" />
            </div>
            <h6 class="text-xl mt-5 font-semibold text-white">Excelent Services</h6>
            <p class="mt-2 mb-4 text-blueGray-400">
              Some quick example text to build on the card title and make up the bulk of the card's
              content.
            </p>
          </div>
          <div class="w-full lg:w-3/12 px-4 text-center">
            <div
              class="text-blueGray-800 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
            >
              <i class="fas fa-poll text-xl" />
            </div>
            <h5 class="text-xl mt-5 font-semibold text-white">Grow your market</h5>
            <p class="mt-2 mb-4 text-blueGray-400">
              Some quick example text to build on the card title and make up the bulk of the card's
              content.
            </p>
          </div>
          <div class="w-full lg:w-3/12 px-4 text-center">
            <div
              class="text-blueGray-800 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center"
            >
              <i class="fas fa-lightbulb text-xl" />
            </div>
            <h5 class="text-xl mt-5 font-semibold text-white">Launch time</h5>
            <p class="mt-2 mb-4 text-blueGray-400">
              Some quick example text to build on the card title and make up the bulk of the card's
              content.
            </p>
          </div>
        </div>
        -->
      </div>
    </section>
    <section class="relative block py-24 lg:pt-0 bg-blueGray-800">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
          <div class="w-full lg:w-6/12 px-4">
            <div
              class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-blueGray-200"
            >
              <div class="flex-auto p-5 lg:p-10">
                <h4 class="text-2xl font-semibold">Quieres contactarnos?</h4>
                <p class="leading-relaxed mt-1 mb-4 text-blueGray-500">
                  Déjanos tus dudas, sugerencias o mensaje en el siguiente formulario y te
                  contactaremos.
                </p>
                <div class="relative w-full mb-3 mt-8">
                  <label
                    class="block uppercase text-blueGray-600 text-xs font-bold mb-2"
                    for="nombre completo"
                  >
                    Nombre Completo
                  </label>
                  <input
                    id="full-name"
                    type="text"
                    class="border-0 px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full ease-linear transition-all duration-150"
                    placeholder="Ejemplo: Maria Soto"
                  />
                </div>

                <div class="relative w-full mb-3">
                  <label
                    class="block uppercase text-blueGray-600 text-xs font-bold mb-2"
                    for="email"
                  >
                    Email
                  </label>
                  <input
                    id="email"
                    type="email"
                    class="border-0 px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full ease-linear transition-all duration-150"
                    placeholder="Ejemplo: msoto@email.com"
                  />
                </div>

                <div class="relative w-full mb-3">
                  <label
                    class="block uppercase text-blueGray-600 text-md font-bold mb-2"
                    for="voluntario"
                  >
                    <input
                      id="voluntario"
                      type="checkbox"
                      class="border-0 px-3 py-3 text-blueGray-600 bg-white rounded shadow focus:outline-none focus:ring ease-linear transition-all duration-150 mr-2"
                      value="volunteer"
                    />
                    <span style="display: inline-block; padding-top: 0.25rem;"
                      >Quiero ser Voluntario!</span
                    >
                  </label>
                </div>

                <div class="relative w-full mb-3">
                  <label
                    class="block uppercase text-blueGray-600 text-xs font-bold mb-2"
                    for="mensaje"
                  >
                    Mensaje
                  </label>
                  <textarea
                    id="message"
                    rows="4"
                    cols="80"
                    class="border-0 px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full"
                    placeholder="Escribe tu mensaje..."
                  />
                </div>
                <div class="text-center mt-6">
                  <button
                    class="logo-indigo text-white active:bg-blueGray-600 text-sm font-bold uppercase px-6 py-3 rounded shadow hover:shadow-lg outline-none focus:outline-none mr-1 mb-1 ease-linear transition-all duration-150"
                    type="button"
                  >
                    Enviar
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
  <Footer />
</div>

<style>
  .pilar-icon {
    font-size: 1.5rem;
  }
  .big-icon {
    font-size: 1.8rem;
  }
</style>
