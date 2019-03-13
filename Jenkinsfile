@Library('sample-lib@master') _

echo 'hello'
println(env['NIO'])
echo "nio id = ${env['NIO']}"
echo(env.toString())

node('master') {
    sh 'echo nio id = $NIO'
    println(env.getEnvironment())
    echo "nio id = ${env['NIO']}"
    sh 'echo nio id = $NIO'
    sh 'echo hello'
    echo(env.toString())
}
