pipeline {
agent any
stages{
// FRONTEND BUILD
stage( 'Build Frontend') {
steps {
dir( 'STUDENTAPI-REACT') {
bat 'npm install'
bat 'npm run build'
}
}
}
}
}