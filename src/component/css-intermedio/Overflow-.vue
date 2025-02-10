<template>
  <div class="contenedor">
    <div class="caja visible">
      <h2>Overflow: visible</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci ab quasi possimus vitae
        rem consequatur ipsa. Laborum ex, exercitationem repudiandae quas incidunt laboriosam illum
        dolor ipsa tenetur repellendus blanditiis harum!
      </p>
    </div>

    <div class="caja hidden">
      <h2>Overflow: hidden</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci ab quasi possimus vitae
        rem consequatur ipsa. Laborum ex, exercitationem repudiandae quas incidunt laboriosam illum
        dolor ipsa tenetur repellendus blanditiis harum!
      </p>
    </div>

    <div class="caja scroll">
      <h2>Overflow: scroll</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci ab quasi possimus vitae
        rem consequatur ipsa. Laborum ex, exercitationem repudiandae quas incidunt laboriosam illum
        dolor ipsa tenetur repellendus blanditiis harum!
      </p>
    </div>

    <div class="caja auto">
      <h2>Overflow: auto</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci ab quasi possimus vitae
        rem consequatur ipsa. Laborum ex, exercitationem repudiandae quas incidunt laboriosam illum
        dolor ipsa tenetur repellendus blanditiis harum!
      </p>
    </div>

    <div class="caja clip">
      <h2>Overflow: clip</h2>
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci ab quasi possimus vitae
        rem consequatur ipsa. Laborum ex, exercitationem repudiandae quas incidunt laboriosam illum
        dolor ipsa tenetur repellendus blanditiis harum!
      </p>
    </div>
  </div>
</template>

<style scoped>
.contenedor {
  width: 100%;
  height: 400px;
}

.caja {
  display: inline-block;
  width: 200px;
  height: 100px;
  border: 2px solid black;
  padding: 10px;
  margin: 80px;
  background-color: #f8f9fa;
}

h2 {
  margin: 0 0 10px 0;
  font-size: 16px;
  color: #333;
}

.visible {
  overflow: visible;
}

.hidden {
  overflow: hidden;
}

.scroll {
  overflow: scroll;
}

.auto {
  overflow: auto;
}

.clip {
  overflow: clip;
}
</style>
