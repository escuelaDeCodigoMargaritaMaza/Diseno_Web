           <h1>Taquería Vikinga ⚔🍻🌮</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Incidunt harum repudiandae, quis accusamus labore assumenda laudantium neque velit, minima eaque consequatur similique laboriosam sed sit! Non corporis delectus cumque fugit esse maiores aspernatur at commodi laboriosam animi debitis, sed reiciendis. Voluptas mollitia rem porro. Doloremque repudiandae accusamus quis necessitatibus! Doloremque laboriosam delectus est dolorem optio dolor vitae voluptatum non autem dicta corrupti animi quam nemo neque eligendi hic ipsam quos officia consequatur sunt, iure alias qui. Tenetur quia labore optio hic. Explicabo repellendus a nam, soluta in quis amet eum non ratione molestias incidunt aperiam consectetur quaerat deserunt sit aut?</p><br>
      
      <video src="img/Vikings - VALHALLA calling me.mp4" autoplay muted loop width="1200"></video>
      <!-- <iframe width="700" height="500" src="https://www.youtube.com/embed/kQAcWVSH2gg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->
      <h2>Menu</h2>
      <h3>Tacos</h3>
      <ul>
          <li>Vikisuadero....$15</li>
          <li>Vikisteck.... $20</li>
          <li>Vikpastor.... $10</li>
          <li>Tripakinga.... $15</li>
          <li>Vikitariano.... $25</li>
          <li>Pollingo.... $15</li>
      </ul><br>
      
      <h3>Bebidas</h3>
      <ol>
          <li>Bebida de Odín....$40</li>
          <li>Agua de Freya....$50</li>
          <li>Hidromiel Valhalla....$60</li>
          <li>Cerveza artesanal Thor....$100</li>
      </ol><br>
      
      <h3>Especialidades</h3>
      <dl>
          <dt>Campechaños</dt>
          <dd>Suadero, tripa y pollo....$50</dd>
          <dt>Vikitariano Valhalla</dt>
          <dd>Champiñones, nopales, cebolla, chile poblano y elotes con queso....$60</dd>
          <dt>Vikingos en México</dt>
          <dd>Nopales, champiñones, quelites y elotes....$50</dd>
          <dt>Ericson el conquitador</dt>
          <dd>Todas las carnes con doble tortilla....$100</dd>
      </dl><br>
      
      <h3>Promociones</h3>
      <table border="1">
          <tr>
              <th colspan="3">Promos</th>
          </tr>
          <tr>
              <th rowspan="7">Días</td>
              <td>Lunes</td>
              <td rowspan="2">2x3</td>
          </tr>
          <tr>
              <td>Martes</td>
          </tr>
          <tr>
              <td>Miércoles</td>
              <td>Todo a $10</td>
          </tr>
          <tr>
              <td>Jueves</td>
              <td>Cervezas a $15</td>
          </tr>
          <tr>
              <td>Viernes</td>
              <td>Queso gratis</td>
          </tr>
          <tr>
              <td>Sádado</td>
              <td rowspan="2">Agua a $10</td>
          </tr>
          <tr>
              <td>Domingo</td>
          </tr>
      </table>
      <br>
      <h2>Ordena YA 😋</h2>
      <FORm name="contact" netlify>
          Nombre: <input type="text" name="nombre" placeholder="juan antonio" size="40" required minlength="3" maxlength="20">
          Direccion: <input type="text" name="direccion" placeholder="Av.De las Flores 116" size="90">
          Telefono: <input type="tel" name="telefono" minlength="10" maxlength="10" required>
          <p>Consumo en local o en envío</p>
          <input type="radio" name="envio" value="local">Local
          <input type="radio" name="envio" value="envio">Envio
          <p>Escoge tu sucursal</p>
          <select name="sucursal">
              <option value="sucursal1">sucursal1</option>
              <option value="sucursal2">sucursal2</option>
              <option value="sucursal3">sucursal3</option>
          </select>
          <p>Escoge tus tacos</p>
          <input type="checkbox" name="vikisuadero" id="si">Vikisuadero
          <input type="number" name="numerosuad" min="0" max="20"><br>
          <input type="checkbox" name="vikisteck" id="si">Vikisteck
          <input type="number" name="numerobistec" min="0" max="20"><br>
          <input type="checkbox" name="vikpastor" id="si">Vikpastor
          <input type="number" name="numeropastor" min="0" max="20"><br>
          <input type="checkbox" name="tripakinga" id="si">Tripakinga
          <input type="number" name="numerotripa" min="0" max="20"><br>
          <input type="checkbox" name="vikitariano" id="si">Vikitariano
          <input type="number" name="numeroveg" min="0" max="20"><br>
          <input type="checkbox" name="pollingo" id="si">Pollingo
          <input type="number" name="numerpollo" min="0" max="20"><br>
          <input type="checkbox" name="limones" id="si">Limones
          <input type="checkbox" name="cebolla" id="si">Cebolla
          <input type="checkbox" name="cilantro" id="si">Cilantro
          <input type="checkbox" name="salsaverde" id="si">Salsa verde
          <input type="checkbox" name="salsaroja" id="si">Salsa roja <br>
          <p>Para cuando es tu pedido</p>
          <input type="date" name="fecha">
          Hora:<input type="time" name="hora"><br>
          <p>Si ya pagaste anexa tu comprobante</p>
          <input type="file" name="comprobante"><br>
          <p>¿Quieres comprobante de tu pedido?</p>
          Correo:<input type="email" name="coreo"><br>
          <input type="submit" value="ordenar⚔">
          <input type="reset" value="limpiar🗑">
      
      </FORm>
      <p>Sucursal matríz</p>
