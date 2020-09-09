<script>
  import 'chota';
  import { Container, Row, Col } from 'svelte-chota';
</script>

<main>
  <Container>
    <h1>Mój Brewlog</h1>
    <Row>
      <Col size="6">
        <h2>Fermentuje</h2>
      </Col>
      <Col size="6">
        <h2>Dojrzewa</h2>
      </Col>
    </Row>
    <Row>
      <Col size="6">
        <h2>Wyszynk</h2>
      </Col>
      <Col size="6">
        <h2>Receptury</h2>
      </Col>
    </Row>
  </Container>
</main>
