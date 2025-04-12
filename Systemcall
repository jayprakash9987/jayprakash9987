<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The System - Advanced AI Optimization</title>
    <style>
        :root {
            --primary-color: #1a2639;
            --secondary-color: #3e7cb1;
            --accent-color: #ff6b6b;
            --background-light: #f4f6f9;
            --background-dark: #e0e6ed;
            --text-dark: #2c3e50;
            --shadow: 0 4px 15px rgba(0,0,0,0.1);
            --transition: all 0.3s ease;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif; 
            background: linear-gradient(145deg, var(--background-light), var(--background-dark));
            color: var(--text-dark);
            line-height: 1.4;
            overflow-x: hidden;
        }
        .navbar {
            position: fixed;
            top: 0;
            width: 100%;
            background: var(--primary-color);
            padding: 1rem 2rem;
            z-index: 2000;
            box-shadow: var(--shadow);
        }
        .nav-inner {
            max-width: 1400px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            color: white;
            font-size: 1.8rem;
            font-weight: 700;
            letter-spacing: 1px;
        }
        .nav-menu {
            display: flex;
            gap: 2rem;
        }
        .nav-item {
            color: white;
            text-decoration: none;
            font-size: 1.1rem;
            transition: var(--transition);
        }
        .nav-item:hover { color: var(--secondary-color); }
        .hero {
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 4rem 2rem;
            background: linear-gradient(to bottom, rgba(0,0,0,0.1), rgba(0,0,0,0.3));
        }
        .hero-title {
            font-size: clamp(2.5rem, 6vw, 5rem);
            margin-bottom: 1.5rem;
            color: var(--primary-color);
            text-shadow: 2px 2px 10px rgba(0,0,0,0.2);
        }
        .hero-subtitle {
            font-size: 1.3rem;
            max-width: 700px;
            margin-bottom: 2rem;
            color: #444;
        }
        .btn-primary {
            background: var(--secondary-color);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 8px;
            font-size: 1.2rem;
            cursor: pointer;
            transition: var(--transition);
            box-shadow: var(--shadow);
        }
        .btn-primary:hover {
            background: #2c5f8d;
            transform: translateY(-3px);
        }
        .section {
            padding: 6rem 2rem;
            background: white;
            border-bottom: 1px solid #eee;
        }
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        .section-title {
            font-size: 2.5rem;
            text-align: center;
            margin-bottom: 3rem;
            color: var(--primary-color);
            position: relative;
        }
        .section-title::after {
            content: '';
            width: 100px;
            height: 4px;
            background: var(--secondary-color);
            position: absolute;
            bottom: -1rem;
            left: 50%;
            transform: translateX(-50%);
        }
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .feature-card {
            background: var(--background-light);
            padding: 2rem;
            border-radius: 12px;
            text-align: center;
            transition: var(--transition);
            box-shadow: var(--shadow);
        }
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 20px rgba(0,0,0,0.15);
        }
        .feature-card h3 {
            color: var(--secondary-color);
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }
        .feature-card p { color: #666; }
        .interface-section {
            background: var(--background-dark);
            padding: 6rem 2rem;
        }
        .interface-wrapper {
            background: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: var(--shadow);
        }
        .control-panel {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-bottom: 2rem;
        }
        .control-btn {
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            transition: var(--transition);
        }
        .btn-start { background: var(--secondary-color); color: white; }
        .btn-stop { background: var(--accent-color); color: white; }
        .btn-analyze { background: #27ae60; color: white; }
        .btn-clear { background: #7f8c8d; color: white; }
        .call-panel {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: 0.8rem;
            margin-bottom: 2rem;
        }
        .call-btn {
            padding: 0.8rem;
            background: var(--background-light);
            border: 1px solid #ddd;
            border-radius: 6px;
            cursor: pointer;
            transition: var(--transition);
        }
        .call-btn:hover {
            background: var(--secondary-color);
            color: white;
            border-color: var(--secondary-color);
        }
        .metrics-panel {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-bottom: 2rem;
        }
        .metric-card {
            background: var(--background-light);
            padding: 1rem;
            border-radius: 8px;
            text-align: center;
        }
        .metric-card h4 { color: var(--secondary-color); margin-bottom: 0.5rem; }
        .log-panel {
            background: var(--background-light);
            padding: 1.5rem;
            border-radius: 8px;
            height: 300px;
            overflow-y: auto;
            font-family: 'Courier New', monospace;
            font-size: 0.9rem;
            border: 1px solid #ddd;
        }
        .config-panel {
            margin-top: 2rem;
            padding: 1.5rem;
            background: var(--background-light);
            border-radius: 8px;
        }
        .config-group {
            margin-bottom: 1rem;
        }
        .config-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 500;
        }
        .config-group input, .config-group select {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .stats-section {
            padding: 6rem 2rem;
            background: white;
        }
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        .stat-card {
            background: var(--background-light);
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
        }
        .stat-card h3 { color: var(--secondary-color); margin-bottom: 0.5rem; }
        .footer {
            background: var(--primary-color);
            color: white;
            padding: 3rem 2rem;
            text-align: center;
        }
        .footer-links {
            margin-top: 1rem;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
        }
        .footer-links a {
            color: var(--secondary-color);
            text-decoration: none;
            transition: var(--transition);
        }
        .footer-links a:hover { color: white; }
        @media (max-width: 768px) {
            .nav-menu { display: none; }
            .hero-title { font-size: 2.5rem; }
            .control-panel { flex-direction: column; }
            .call-panel { grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)); }
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="nav-inner">
            <div class="logo">The System</div>
            <div class="nav-menu">
                <a href="#home" class="nav-item">Home</a>
                <a href="#features" class="nav-item">Features</a>
                <a href="#interface" class="nav-item">Interface</a>
                <a href="#stats" class="nav-item">Stats</a>
                <a href="#contact" class="nav-item">Contact</a>
            </div>
        </div>
    </nav>

    <section class="hero" id="home">
        <h1 class="hero-title">AI-Enhanced System call Optimization</h1>
        <p class="hero-subtitle">Unleash unparalleled system performance with our AI-driven optimization technology</p>
        <button class="btn-primary" onclick="scrollToSection('interface')">Explore Interface</button>
    </section>

    <section class="section" id="features">
        <div class="container">
            <h2 class="section-title">Advanced Features</h2>
            <div class="features-grid">
                <div class="feature-card">
                    <h3>Dynamic Optimization</h3>
                    <p>Real-time system call enhancement with adaptive AI algorithms</p>
                </div>
                <div class="feature-card">
                    <h3>Resource Prediction</h3>
                    <p>Proactive resource allocation based on workload analysis</p>
                </div>
                <div class="feature-card">
                    <h3>Security Monitoring</h3>
                    <p>Advanced threat detection through call pattern analysis</p>
                </div>
                <div class="feature-card">
                    <h3>Performance Tuning</h3>
                    <p>Automated system parameter optimization</p>
                </div>
                <div class="feature-card">
                    <h3>Load Balancing</h3>
                    <p>Intelligent distribution of system resources</p>
                </div>
                <div class="feature-card">
                    <h3>Error Recovery</h3>
                    <p>AI-assisted system call error handling</p>
                </div>
            </div>
        </div>
    </section>

    <section class="interface-section" id="interface">
        <div class="container">
            <h2 class="section-title">Optimization Interface</h2>
            <div class="interface-wrapper">
                <div class="control-panel">
                    <button class="control-btn btn-start" onclick="startOptimization()">Start</button>
                    <button class="control-btn btn-stop" onclick="stopOptimization()">Stop</button>
                    <button class="control-btn btn-analyze" onclick="analyzeSystem()">Analyze</button>
                    <button class="control-btn btn-clear" onclick="clearLogs()">Clear</button>
                </div>
                <div class="call-panel" id="callPanel"></div>
                <div class="metrics-panel" id="metricsPanel"></div>
                <div class="log-panel" id="logPanel"></div>
                <div class="config-panel">
                    <h3>Configuration</h3>
                    <div class="config-group">
                        <label>Optimization Level</label>
                        <select id="optLevel">
                            <option value="low">Low</option>
                            <option value="medium">Medium</option>
                            <option value="high">High</option>
                        </select>
                    </div>
                    <div class="config-group">
                        <label>Interval (ms)</label>
                        <input type="number" id="optInterval" value="1000" min="100" max="5000">
                    </div>
                    <div class="config-group">
                        <label>Resource Limit (%)</label>
                        <input type="number" id="resourceLimit" value="80" min="10" max="100">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="stats-section" id="stats">
        <div class="container">
            <h2 class="section-title">System Statistics</h2>
            <div class="stats-grid" id="statsGrid"></div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>Built with grit and coffee by the System Crew - 2025</p>
            <div class="footer-links">
                <a href="#">About Us</a>
                <a href="#">Support</a>
                <a href="#">Docs</a>
                <a href="#">Get in Touch</a>
            </div>
        </div>
    </footer>
    
    <style>
        .footer {
            background: #1f2d40;
            color: #fff;
            padding: 40px 20px;
            text-align: center;
        }
        .footer-links {
            margin-top: 15px;
        }
        .footer-links a {
            color: #4a90e2;
            text-decoration: none;
            margin: 0 15px;
            font-size: 14px;
        }
        .footer-links a:hover {
            color: #fff;
        }
    </style>

    <script>
        class AdvancedSystemOptimizer {
            constructor() {
                this.running = false;
                this.intervalId = null;
                this.callTypes = [
                    {name: 'read', baseTime: 200, resource: 10},
                    {name: 'write', baseTime: 250, resource: 15},
                    {name: 'open', baseTime: 150, resource: 8},
                    {name: 'close', baseTime: 100, resource: 5},
                    {name: 'fork', baseTime: 400, resource: 25},
                    {name: 'exec', baseTime: 350, resource: 20},
                    {name: 'mmap', baseTime: 300, resource: 18},
                    {name: 'munmap', baseTime: 280, resource: 16}
                ];
                this.metrics = {
                    totalCalls: 0,
                    avgLatency: 0,
                    throughput: 0,
                    efficiency: 0,
                    resourceUsage: 0,
                    errorRate: 0
                };
                this.history = [];
                this.config = {
                    level: 'medium',
                    interval: 1000,
                    resourceLimit: 80
                };
                this.initInterface();
                this.bindConfig();
            }

            initInterface() {
                const callPanel = document.getElementById('callPanel');
                this.callTypes.forEach(call => {
                    const btn = document.createElement('button');
                    btn.className = 'call-btn';
                    btn.textContent = call.name;
                    btn.onclick = () => this.executeSingleCall(call.name);
                    callPanel.appendChild(btn);
                });

                this.updateMetrics();
                this.updateStats();
            }

            bindConfig() {
                document.getElementById('optLevel').addEventListener('change', (e) => {
                    this.config.level = e.target.value;
                    this.log(`Optimization level set to ${this.config.level}`);
                });
                document.getElementById('optInterval').addEventListener('change', (e) => {
                    this.config.interval = parseInt(e.target.value);
                    if (this.running) {
                        this.stop();
                        this.start();
                    }
                    this.log(`Interval updated to ${this.config.interval}ms`);
                });
                document.getElementById('resourceLimit').addEventListener('change', (e) => {
                    this.config.resourceLimit = parseInt(e.target.value);
                    this.log(`Resource limit set to ${this.config.resourceLimit}%`);
                });
            }

            log(message) {
                const logPanel = document.getElementById('logPanel');
                logPanel.innerHTML += `[${new Date().toLocaleTimeString()}] ${message}<br>`;
                logPanel.scrollTop = logPanel.scrollHeight;
            }

            updateMetrics() {
                const metricsPanel = document.getElementById('metricsPanel');
                metricsPanel.innerHTML = `
                    <div class="metric-card">
                        <h4>Total Calls</h4>
                        <p>${this.metrics.totalCalls}</p>
                    </div>
                    <div class="metric-card">
                        <h4>Avg Latency</h4>
                        <p>${this.metrics.avgLatency.toFixed(2)}ms</p>
                    </div>
                    <div class="metric-card">
                        <h4>Throughput</h4>
                        <p>${this.metrics.throughput.toFixed(2)} calls/s</p>
                    </div>
                    <div class="metric-card">
                        <h4>Efficiency</h4>
                        <p>${this.metrics.efficiency.toFixed(2)}%</p>
                    </div>
                    <div class="metric-card">
                        <h4>Resource Usage</h4>
                        <p>${this.metrics.resourceUsage.toFixed(2)}%</p>
                    </div>
                    <div class="metric-card">
                        <h4>Error Rate</h4>
                        <p>${this.metrics.errorRate.toFixed(2)}%</p>
                    </div>
                `;
            }

            updateStats() {
                const statsGrid = document.getElementById('statsGrid');
                statsGrid.innerHTML = `
                    <div class="stat-card">
                        <h3>Optimization Rate</h3>
                        <p>${(this.metrics.efficiency * 0.8).toFixed(2)}%</p>
                    </div>
                    <div class="stat-card">
                        <h3>Resource Efficiency</h3>
                        <p>${(100 - this.metrics.resourceUsage).toFixed(2)}%</p>
                    </div>
                    <div class="stat-card">
                        <h3>Call Distribution</h3>
                        <p>${this.getCallDistribution()}</p>
                    </div>
                    <div class="stat-card">
                        <h3>System Stability</h3>
                        <p>${(100 - this.metrics.errorRate).toFixed(2)}%</p>
                    </div>
                `;
            }

            getCallDistribution() {
                const counts = this.history.reduce((acc, h) => {
                    acc[h.call] = (acc[h.call] || 0) + 1;
                    return acc;
                }, {});
                return Object.entries(counts)
                    .map(([call, count]) => `${call}: ${count}`)
                    .join(', ');
            }

            optimizeCall(callType) {
                const call = this.callTypes.find(c => c.name === callType);
                const baseTime = call.baseTime * (0.8 + Math.random() * 0.4);
                let optFactor;
                switch(this.config.level) {
                    case 'low': optFactor = 0.7; break;
                    case 'medium': optFactor = 0.5; break;
                    case 'high': optFactor = 0.3; break;
                }
                const optimizedTime = baseTime * optFactor;
                const resource = call.resource * (0.8 + Math.random() * 0.4);
                const error = Math.random() < 0.05 ? true : false;

                if (resource > this.config.resourceLimit) {
                    return { error: true, message: 'Resource limit exceeded' };
                }

                const efficiency = ((baseTime - optimizedTime) / baseTime) * 100;
                this.metrics.totalCalls++;
                this.metrics.avgLatency = (this.metrics.avgLatency * (this.metrics.totalCalls - 1) + optimizedTime) / this.metrics.totalCalls;
                this.metrics.throughput = 1000 / this.metrics.avgLatency;
                this.metrics.efficiency = (this.metrics.efficiency * (this.metrics.totalCalls - 1) + efficiency) / this.metrics.totalCalls;
                this.metrics.resourceUsage = (this.metrics.resourceUsage * (this.metrics.totalCalls - 1) + resource) / this.metrics.totalCalls;
                this.metrics.errorRate = (this.metrics.errorRate * (this.metrics.totalCalls - 1) + (error ? 100 : 0)) / this.metrics.totalCalls;

                this.history.push({ call: callType, baseTime, optimizedTime, resource, error });
                return { baseTime, optimizedTime, resource, efficiency, error };
            }

            executeSingleCall(callType) {
                const result = this.optimizeCall(callType);
                if (result.error) {
                    this.log(`ERROR: ${callType} - ${result.message}`);
                } else {
                    this.log(`${callType}: ${result.baseTime.toFixed(2)}ms → ${result.optimizedTime.toFixed(2)}ms`);
                    this.log(`- Efficiency: ${result.efficiency.toFixed(2)}%`);
                    this.log(`- Resources: ${result.resource.toFixed(2)}%`);
                    if (result.error) this.log('- Status: FAILED');
                }
                this.updateMetrics();
                this.updateStats();
            }

            autoOptimize() {
                if (!this.running) return;
                const callType = this.callTypes[Math.floor(Math.random() * this.callTypes.length)].name;
                this.executeSingleCall(callType);
                this.intervalId = setTimeout(() => this.autoOptimize(), this.config.interval);
            }

            start() {
                if (!this.running) {
                    this.running = true;
                    this.log('System optimization started');
                    this.autoOptimize();
                }
            }

            stop() {
                if (this.running) {
                    clearTimeout(this.intervalId);
                    this.running = false;
                    this.log('System optimization stopped');
                    this.analyzeSystem();
                }
            }

            analyzeSystem() {
                if (!this.history.length) {
                    this.log('No optimization data available');
                    return;
                }
                const totalTimeSaved = this.history.reduce((sum, h) => sum + (h.baseTime - h.optimizedTime), 0);
                const avgResource = this.history.reduce((sum, h) => sum + h.resource, 0) / this.history.length;
                const errorCount = this.history.filter(h => h.error).length;
                this.log('--- System Analysis ---');
                this.log(`Total time saved: ${totalTimeSaved.toFixed(2)}ms`);
                this.log(`Average resource usage: ${avgResource.toFixed(2)}%`);
                this.log(`Error count: ${errorCount} (${(errorCount / this.history.length * 100).toFixed(2)}%)`);
                this.log(`Call distribution: ${this.getCallDistribution()}`);
            }

            clear() {
                document.getElementById('logPanel').innerHTML = '';
                this.history = [];
                this.metrics = {
                    totalCalls: 0,
                    avgLatency: 0,
                    throughput: 0,
                    efficiency: 0,
                    resourceUsage: 0,
                    errorRate: 0
                };
                this.updateMetrics();
                this.updateStats();
                this.log('Logs and history cleared');
            }
        }

        const optimizer = new AdvancedSystemOptimizer();

        function startOptimization() { optimizer.start(); }
        function stopOptimization() { optimizer.stop(); }
        function analyzeSystem() { optimizer.analyzeSystem(); }
        function clearLogs() { optimizer.clear(); }

        function scrollToSection(sectionId) {
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
        }

        window.addEventListener('scroll', () => {
            const sections = document.querySelectorAll('section');
            const navItems = document.querySelectorAll('.nav-item');
            let currentSection = '';
            sections.forEach(section => {
                if (window.pageYOffset >= section.offsetTop - 60) {
                    currentSection = section.id;
                }
            });
            navItems.forEach(item => {
                item.classList.toggle('active', item.getAttribute('href').slice(1) === currentSection);
            });
        });

        const style = document.createElement('style');
        style.textContent = `
            .nav-item.active {
                color: var(--secondary-color);
                border-bottom: 2px solid var(--secondary-color);
                padding-bottom: 0.2rem;
            }
            @keyframes fadeIn {
                from { opacity: 0; transform: translateY(20px); }
                to { opacity: 1; transform: translateY(0); }
            }
            .feature-card, .metric-card, .stat-card {
                animation: fadeIn 0.5s ease-out;
            }
        `;
        document.head.appendChild(style);

        document.addEventListener('DOMContentLoaded', () => {
            const cards = document.querySelectorAll('.feature-card, .metric-card, .stat-card');
            cards.forEach((card, i) => {
                card.style.animationDelay = `${i * 0.1}s`;
            });
        });
    </script>
</body>
</html>
