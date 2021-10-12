# goolte-lab.github.io
<pre>
create repo name as username.github.io 
git clone https://github.com/goolte-lab/goolte-lab.github.io
cd goolte-lab.github.io/
echo "hell World" > index.html
git add --all
git commit -m "init"
git push -u origin main
pwd
mkdir helm-charts
cd helm-charts/
helm create helm-chart-test
helm package helm-chart-test/
cd ..
git add --all
cd helm-charts/
ls
helm repo index --url https://goolte-lab.github.io/helm-charts/ .
git add --all
cd ..
git add --all
git commit -m "init"
git push -u origin main
</pre>
