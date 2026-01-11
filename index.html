<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project Gateway AI Simulation Lab</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary-color: #0a192f;
            --secondary-color: #112240;
            --accent-color: #64ffda;
            --text-color: #e6f1ff;
            --focus-10: #1a5fb4;
            --focus-15: #26a269;
            --focus-21: #c061cb;
            --danger: #ff4757;
            --warning: #ffa502;
            --success: #2ed573;
        }

        body {
            background: linear-gradient(135deg, var(--primary-color), #020c1b);
            color: var(--text-color);
            min-height: 100vh;
            overflow-x: hidden;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 2rem 0;
            border-bottom: 1px solid rgba(100, 255, 218, 0.2);
            margin-bottom: 2rem;
        }

        .logo {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 15px;
            margin-bottom: 1rem;
        }

        .logo-icon {
            width: 50px;
            height: 50px;
            background: var(--accent-color);
            border-radius: 50%;
            position: relative;
        }

        .logo-icon::before {
            content: '';
            position: absolute;
            width: 30px;
            height: 30px;
            border: 3px solid var(--primary-color);
            border-top-color: transparent;
            border-radius: 50%;
            animation: spin 3s linear infinite;
            top: 7px;
            left: 7px;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        h1 {
            font-size: 2.5rem;
            background: linear-gradient(45deg, var(--accent-color), #4dabf7);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 0.5rem;
        }

        .subtitle {
            color: #8892b0;
            font-size: 1.1rem;
        }

        .main-grid {
            display: grid;
            grid-template-columns: 300px 1fr 350px;
            gap: 20px;
            height: calc(100vh - 200px);
        }

        /* Control Panel */
        .control-panel {
            background: rgba(17, 34, 64, 0.8);
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(100, 255, 218, 0.1);
        }

        .control-section {
            margin-bottom: 25px;
        }

        .control-section h3 {
            color: var(--accent-color);
            margin-bottom: 15px;
            font-size: 1.1rem;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .control-section h3 i {
            font-size: 1.2rem;
        }

        .frequency-controls {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }

        .frequency-control {
            background: rgba(255, 255, 255, 0.05);
            padding: 12px;
            border-radius: 8px;
            text-align: center;
        }

        .frequency-control label {
            display: block;
            margin-bottom: 5px;
            font-size: 0.9rem;
            color: #8892b0;
        }

        .frequency-value {
            font-size: 1.2rem;
            color: var(--accent-color);
            font-weight: bold;
        }

        .focus-levels {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        .focus-btn {
            padding: 12px;
            border: none;
            border-radius: 8px;
            background: rgba(255, 255, 255, 0.05);
            color: var(--text-color);
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .focus-btn:hover {
            transform: translateX(5px);
            background: rgba(255, 255, 255, 0.1);
        }

        .focus-btn.active {
            background: linear-gradient(90deg, rgba(100, 255, 218, 0.2), transparent);
            border-left: 3px solid var(--accent-color);
        }

        .focus-level {
            font-weight: bold;
        }

        .focus-desc {
            font-size: 0.8rem;
            color: #8892b0;
        }

        .slider-container {
            margin-top: 10px;
        }

        .slider {
            width: 100%;
            height: 6px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
            outline: none;
            -webkit-appearance: none;
        }

        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 20px;
            height: 20px;
            background: var(--accent-color);
            border-radius: 50%;
            cursor: pointer;
        }

        .control-buttons {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            margin-top: 20px;
        }

        .btn {
            padding: 12px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }

        .btn-primary {
            background: linear-gradient(45deg, var(--accent-color), #4dabf7);
            color: var(--primary-color);
        }

        .btn-secondary {
            background: rgba(255, 255, 255, 0.1);
            color: var(--text-color);
        }

        .btn-danger {
            background: var(--danger);
            color: white;
        }

        /* Visualization Area */
        .visualization-area {
            background: rgba(10, 25, 47, 0.9);
            border-radius: 15px;
            padding: 20px;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(100, 255, 218, 0.1);
        }

        .brain-visualization {
            width: 100%;
            height: 100%;
            position: relative;
        }

        .brain-lobe {
            position: absolute;
            border-radius: 50%;
            opacity: 0.7;
            transition: all 0.5s ease;
        }

        .frontal-lobe {
            width: 120px;
            height: 120px;
            background: radial-gradient(circle, var(--focus-10), transparent);
            top: 30%;
            left: 45%;
        }

        .temporal-lobe {
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, var(--focus-15), transparent);
            top: 50%;
            left: 30%;
        }

        .parietal-lobe {
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, var(--focus-21), transparent);
            top: 50%;
            right: 30%;
        }

        .occipital-lobe {
            width: 80px;
            height: 80px;
            background: radial-gradient(circle, #ffa502, transparent);
            bottom: 30%;
            left: 45%;
        }

        .brain-waves {
            position: absolute;
            bottom: 20px;
            left: 0;
            right: 0;
            height: 150px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            padding: 10px;
        }

        .wave-canvas {
            width: 100%;
            height: 100%;
        }

        .current-state {
            position: absolute;
            top: 20px;
            left: 20px;
            background: rgba(0, 0, 0, 0.5);
            padding: 15px;
            border-radius: 10px;
            min-width: 200px;
        }

        .state-label {
            color: #8892b0;
            font-size: 0.9rem;
            margin-bottom: 5px;
        }

        .state-value {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--accent-color);
        }

        /* Data Panel */
        .data-panel {
            background: rgba(17, 34, 64, 0.8);
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(100, 255, 218, 0.1);
            overflow-y: auto;
        }

        .metrics-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 25px;
        }

        .metric-card {
            background: rgba(255, 255, 255, 0.05);
            padding: 15px;
            border-radius: 10px;
            text-align: center;
        }

        .metric-value {
            font-size: 2rem;
            font-weight: bold;
            color: var(--accent-color);
            margin: 10px 0;
        }

        .metric-label {
            font-size: 0.8rem;
            color: #8892b0;
        }

        .log-container {
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            padding: 15px;
            height: 300px;
            overflow-y: auto;
        }

        .log-entry {
            padding: 10px;
            margin-bottom: 8px;
            border-left: 3px solid;
            background: rgba(255, 255, 255, 0.05);
            border-radius: 0 5px 5px 0;
            font-size: 0.9rem;
        }

        .log-info { border-color: var(--accent-color); }
        .log-warning { border-color: var(--warning); }
        .log-danger { border-color: var(--danger); }
        .log-success { border-color: var(--success); }

        .log-time {
            color: #8892b0;
            font-size: 0.8rem;
            margin-right: 10px;
        }

        /* Session Info */
        .session-info {
            margin-top: 20px;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        .progress-bar {
            height: 6px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
            margin: 10px 0;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--accent-color), #4dabf7);
            width: 0%;
            transition: width 0.5s ease;
        }

        /* Audio Visualizer */
        .audio-visualizer {
            width: 100%;
            height: 80px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px;
            margin-top: 20px;
            position: relative;
            overflow: hidden;
        }

        .frequency-bar {
            position: absolute;
            bottom: 0;
            width: 4px;
            background: var(--accent-color);
            border-radius: 2px 2px 0 0;
            transition: height 0.1s ease;
        }

        /* Modal */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            z-index: 1000;
            align-items: center;
            justify-content: center;
        }

        .modal.active {
            display: flex;
        }

        .modal-content {
            background: var(--secondary-color);
            padding: 30px;
            border-radius: 15px;
            max-width: 500px;
            width: 90%;
            border: 1px solid var(--accent-color);
        }

        .modal h2 {
            color: var(--accent-color);
            margin-bottom: 20px;
        }

        /* Responsive Design */
        @media (max-width: 1200px) {
            .main-grid {
                grid-template-columns: 1fr;
                height: auto;
            }
            
            .control-panel,
            .data-panel {
                height: auto;
                margin-bottom: 20px;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <div class="logo-icon"></div>
                <div>
                    <h1>Project Gateway AI Simulation Lab</h1>
                    <p class="subtitle">Exploring Consciousness Through Hemi-Sync® Technology Simulation</p>
                </div>
            </div>
        </header>

        <div class="main-grid">
            <!-- Control Panel -->
            <div class="control-panel">
                <div class="control-section">
                    <h3><i class="fas fa-wave-square"></i> Hemi-Sync® Controls</h3>
                    <div class="frequency-controls">
                        <div class="frequency-control">
                            <label>Left Hemisphere</label>
                            <div class="frequency-value" id="leftFreq">440 Hz</div>
                        </div>
                        <div class="frequency-control">
                            <label>Right Hemisphere</label>
                            <div class="frequency-value" id="rightFreq">449 Hz</div>
                        </div>
                    </div>
                    <div class="slider-container">
                        <input type="range" min="0.5" max="30" step="0.5" value="9" class="slider" id="frequencySlider">
                    </div>
                    <div class="audio-visualizer" id="audioVisualizer"></div>
                </div>

                <div class="control-section">
                    <h3><i class="fas fa-brain"></i> Focus Levels</h3>
                    <div class="focus-levels">
                        <button class="focus-btn active" data-level="10">
                            <div>
                                <div class="focus-level">Focus 10</div>
                                <div class="focus-desc">Mind Awake, Body Asleep</div>
                            </div>
                            <i class="fas fa-check-circle"></i>
                        </button>
                        <button class="focus-btn" data-level="12">
                            <div>
                                <div class="focus-level">Focus 12</div>
                                <div class="focus-desc">Expanded Awareness</div>
                            </div>
                            <i class="fas fa-arrow-right"></i>
                        </button>
                        <button class="focus-btn" data-level="15">
                            <div>
                                <div class="focus-level">Focus 15</div>
                                <div class="focus-desc">No Time State</div>
                            </div>
                            <i class="fas fa-clock"></i>
                        </button>
                        <button class="focus-btn" data-level="21">
                            <div>
                                <div class="focus-level">Focus 21</div>
                                <div class="focus-desc">Beyond Physical</div>
                            </div>
                            <i class="fas fa-infinity"></i>
                        </button>
                    </div>
                </div>

                <div class="control-section">
                    <h3><i class="fas fa-cogs"></i> Session Controls</h3>
                    <div class="control-buttons">
                        <button class="btn btn-primary" id="startBtn">
                            <i class="fas fa-play"></i> Start Session
                        </button>
                        <button class="btn btn-secondary" id="pauseBtn">
                            <i class="fas fa-pause"></i> Pause
                        </button>
                        <button class="btn btn-secondary" id="resetBtn">
                            <i class="fas fa-redo"></i> Reset
                        </button>
                        <button class="btn btn-danger" id="emergencyBtn">
                            <i class="fas fa-first-aid"></i> Emergency Return
                        </button>
                    </div>
                </div>

                <div class="control-section">
                    <h3><i class="fas fa-sliders-h"></i> AI Parameters</h3>
                    <div class="slider-container">
                        <label>Consciousness Depth</label>
                        <input type="range" min="1" max="100" value="50" class="slider" id="depthSlider">
                    </div>
                    <div class="slider-container">
                        <label>Neural Synchronization</label>
                        <input type="range" min="1" max="100" value="75" class="slider" id="syncSlider">
                    </div>
                </div>
            </div>

            <!-- Visualization Area -->
            <div class="visualization-area">
                <div class="current-state">
                    <div class="state-label">Current State</div>
                    <div class="state-value" id="currentState">Focus 10</div>
                    <div class="state-label" id="stateDescription">Mind Awake, Body Asleep</div>
                </div>

                <div class="brain-visualization">
                    <div class="brain-lobe frontal-lobe" id="frontalLobe"></div>
                    <div class="brain-lobe temporal-lobe" id="temporalLobe"></div>
                    <div class="brain-lobe parietal-lobe" id="parietalLobe"></div>
                    <div class="brain-lobe occipital-lobe" id="occipitalLobe"></div>
                    
                    <div class="brain-waves">
                        <canvas class="wave-canvas" id="waveCanvas"></canvas>
                    </div>
                </div>
            </div>

            <!-- Data Panel -->
            <div class="data-panel">
                <div class="metrics-grid">
                    <div class="metric-card">
                        <div class="metric-label">Neural Coherence</div>
                        <div class="metric-value" id="coherenceValue">78%</div>
                    </div>
                    <div class="metric-card">
                        <div class="metric-label">Session Time</div>
                        <div class="metric-value" id="sessionTime">00:00</div>
                    </div>
                    <div class="metric-card">
                        <div class="metric-label">Brainwave State</div>
                        <div class="metric-value" id="brainwaveState">Theta</div>
                    </div>
                    <div class="metric-card">
                        <div class="metric-label">Focus Stability</div>
                        <div class="metric-value" id="stabilityValue">92%</div>
                    </div>
                </div>

                <div class="control-section">
                    <h3><i class="fas fa-clipboard-list"></i> Session Log</h3>
                    <div class="log-container" id="logContainer">
                        <div class="log-entry log-info">
                            <span class="log-time">00:00:00</span>
                            Session initialized
                        </div>
                        <div class="log-entry log-info">
                            <span class="log-time">00:00:00</span>
                            Hemi-Sync® frequencies calibrated
                        </div>
                    </div>
                </div>

                <div class="session-info">
                    <h3><i class="fas fa-chart-line"></i> Session Progress</h3>
                    <div class="progress-bar">
                        <div class="progress-fill" id="progressFill"></div>
                    </div>
                    <div style="display: flex; justify-content: space-between; font-size: 0.9rem;">
                        <span>Energy Conversion Box</span>
                        <span>Remote Viewing</span>
                    </div>
                </div>

                <div class="control-section">
                    <h3><i class="fas fa-microchip"></i> AI Processing</h3>
                    <div id="aiProcessing">
                        <div style="margin-bottom: 10px;">
                            <div style="display: flex; justify-content: space-between;">
                                <span>Pattern Recognition</span>
                                <span id="patternRecognition">75%</span>
                            </div>
                            <div class="progress-bar" style="height: 4px;">
                                <div class="progress-fill" style="width: 75%;"></div>
                            </div>
                        </div>
                        <div style="margin-bottom: 10px;">
                            <div style="display: flex; justify-content: space-between;">
                                <span>State Prediction</span>
                                <span id="statePrediction">88%</span>
                            </div>
                            <div class="progress-bar" style="height: 4px;">
                                <div class="progress-fill" style="width: 88%;"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Modal for Emergency Return -->
    <div class="modal" id="emergencyModal">
        <div class="modal-content">
            <h2><i class="fas fa-exclamation-triangle"></i> Emergency Return Protocol</h2>
            <p>Initiating immediate reintegration sequence. Please remain calm.</p>
            <div style="margin: 20px 0;">
                <div class="progress-bar">
                    <div class="progress-fill" id="emergencyProgress"></div>
                </div>
            </div>
            <p>Focus on your physical body. You will be fully reintegrated in:</p>
            <h2 style="text-align: center; margin: 20px 0;" id="countdown">5</h2>
            <button class="btn btn-primary" id="confirmReturn" style="width: 100%;">
                Confirm Reintegration
            </button>
        </div>
    </div>

    <script>
        // Global Variables
        let sessionActive = false;
        let sessionStartTime = null;
        let currentFocusLevel = 10;
        let sessionTimer = null;
        let waveData = [];
        let audioContext = null;
        let oscillatorLeft = null;
        let oscillatorRight = null;
        let gainNode = null;

        // Focus Level Definitions
        const focusLevels = {
            10: {
                name: "Focus 10",
                description: "Mind Awake, Body Asleep",
                leftFreq: 440,
                rightFreq: 449,
                brainwave: "Theta",
                color: "#1a5fb4"
            },
            12: {
                name: "Focus 12",
                description: "Expanded Awareness",
                leftFreq: 432,
                rightFreq: 440,
                brainwave: "Alpha",
                color: "#26a269"
            },
            15: {
                name: "Focus 15",
                description: "No Time State",
                leftFreq: 417,
                rightFreq: 425,
                brainwave: "Alpha-Theta",
                color: "#3584e4"
            },
            21: {
                name: "Focus 21",
                description: "Beyond Physical",
                leftFreq: 396,
                rightFreq: 405,
                brainwave: "Delta",
                color: "#c061cb"
            }
        };

        // DOM Elements
        const startBtn = document.getElementById('startBtn');
        const pauseBtn = document.getElementById('pauseBtn');
        const resetBtn = document.getElementById('resetBtn');
        const emergencyBtn = document.getElementById('emergencyBtn');
        const frequencySlider = document.getElementById('frequencySlider');
        const focusButtons = document.querySelectorAll('.focus-btn');
        const currentState = document.getElementById('currentState');
        const stateDescription = document.getElementById('stateDescription');
        const sessionTime = document.getElementById('sessionTime');
        const brainwaveState = document.getElementById('brainwaveState');
        const coherenceValue = document.getElementById('coherenceValue');
        const stabilityValue = document.getElementById('stabilityValue');
        const leftFreq = document.getElementById('leftFreq');
        const rightFreq = document.getElementById('rightFreq');
        const logContainer = document.getElementById('logContainer');
        const progressFill = document.getElementById('progressFill');
        const waveCanvas = document.getElementById('waveCanvas');
        const audioVisualizer = document.getElementById('audioVisualizer');
        const emergencyModal = document.getElementById('emergencyModal');
        const confirmReturn = document.getElementById('confirmReturn');
        const countdown = document.getElementById('countdown');
        const emergencyProgress = document.getElementById('emergencyProgress');

        // Brain lobes
        const frontalLobe = document.getElementById('frontalLobe');
        const temporalLobe = document.getElementById('temporalLobe');
        const parietalLobe = document.getElementById('parietalLobe');
        const occipitalLobe = document.getElementById('occipitalLobe');

        // Initialize Audio Context
        function initAudio() {
            try {
                audioContext = new (window.AudioContext || window.webkitAudioContext)();
                
                // Create nodes
                gainNode = audioContext.createGain();
                gainNode.connect(audioContext.destination);
                gainNode.gain.value = 0;
                
                log("Audio context initialized", "success");
            } catch (e) {
                log("Web Audio API not supported: " + e.message, "danger");
            }
        }

        // Start Hemi-Sync Audio
        function startHemiSync(leftFreqVal, rightFreqVal) {
            if (!audioContext) return;
            
            stopHemiSync();
            
            oscillatorLeft = audioContext.createOscillator();
            oscillatorRight = audioContext.createOscillator();
            
            oscillatorLeft.frequency.value = leftFreqVal;
            oscillatorRight.frequency.value = rightFreqVal;
            
            // Create panner for stereo effect
            const pannerLeft = audioContext.createStereoPanner();
            const pannerRight = audioContext.createStereoPanner();
            pannerLeft.pan.value = -1; // Left channel
            pannerRight.pan.value = 1; // Right channel
            
            oscillatorLeft.connect(pannerLeft).connect(gainNode);
            oscillatorRight.connect(pannerRight).connect(gainNode);
            
            oscillatorLeft.start();
            oscillatorRight.start();
            
            // Fade in
            gainNode.gain.linearRampToValueAtTime(0.1, audioContext.currentTime + 2);
            
            log(`Hemi-Sync started: L=${leftFreqVal}Hz, R=${rightFreqVal}Hz`, "info");
        }

        // Stop Hemi-Sync Audio
        function stopHemiSync() {
            if (gainNode) {
                gainNode.gain.linearRampToValueAtTime(0, audioContext.currentTime + 1);
            }
            
            if (oscillatorLeft) {
                setTimeout(() => {
                    oscillatorLeft.stop();
                    oscillatorRight.stop();
                }, 1000);
            }
        }

        // Update Brain Visualization
        function updateBrainVisualization() {
            const level = focusLevels[currentFocusLevel];
            
            // Animate brain lobes
            frontalLobe.style.background = `radial-gradient(circle, ${level.color}, transparent)`;
            temporalLobe.style.background = `radial-gradient(circle, ${level.color}aa, transparent)`;
            parietalLobe.style.background = `radial-gradient(circle, ${level.color}88, transparent)`;
            occipitalLobe.style.background = `radial-gradient(circle, ${level.color}66, transparent)`;
            
            // Pulsing effect
            const pulse = 1 + Math.sin(Date.now() / 1000) * 0.1;
            frontalLobe.style.transform = `scale(${pulse})`;
            temporalLobe.style.transform = `scale(${1 + Math.sin(Date.now() / 1200) * 0.1})`;
            
            updateAudioVisualizer();
        }

        // Update Audio Visualizer
        function updateAudioVisualizer() {
            const visualizer = document.getElementById('audioVisualizer');
            visualizer.innerHTML = '';
            
            for (let i = 0; i < 32; i++) {
                const bar = document.createElement('div');
                bar.className = 'frequency-bar';
                bar.style.left = `${i * (100 / 32)}%`;
                bar.style.height = `${20 + Math.sin(Date.now() / 100 + i) * 40}px`;
                visualizer.appendChild(bar);
            }
        }

        // Update Wave Visualization
        function updateWaveVisualization() {
            const ctx = waveCanvas.getContext('2d');
            const width = waveCanvas.width = waveCanvas.offsetWidth;
            const height = waveCanvas.height = waveCanvas.offsetHeight;
            
            ctx.clearRect(0, 0, width, height);
            
            // Generate wave data
            waveData.push(Math.sin(Date.now() / 1000));
            if (waveData.length > width / 2) waveData.shift();
            
            // Draw waves
            ctx.strokeStyle = focusLevels[currentFocusLevel].color;
            ctx.lineWidth = 2;
            ctx.beginPath();
            
            for (let i = 0; i < waveData.length; i++) {
                const x = i * 2;
                const y = height / 2 + waveData[i] * 40;
                
                if (i === 0) ctx.moveTo(x, y);
                else ctx.lineTo(x, y);
            }
            
            ctx.stroke();
            
            // Draw brainwave type
            ctx.fillStyle = '#8892b0';
            ctx.font = '12px Arial';
            ctx.fillText(focusLevels[currentFocusLevel].brainwave + ' Waves', 10, 20);
        }

        // Start Session
        function startSession() {
            if (sessionActive) return;
            
            sessionActive = true;
            sessionStartTime = Date.now();
            
            startHemiSync(focusLevels[currentFocusLevel].leftFreq, 
                         focusLevels[currentFocusLevel].rightFreq);
            
            sessionTimer = setInterval(updateSession, 100);
            
            log("Session started", "success");
            startBtn.innerHTML = '<i class="fas fa-play"></i> Session Active';
            startBtn.disabled = true;
            pauseBtn.disabled = false;
            
            // Start progress
            let progress = 0;
            const progressInterval = setInterval(() => {
                if (!sessionActive) {
                    clearInterval(progressInterval);
                    return;
                }
                progress = Math.min(100, progress + 0.1);
                progressFill.style.width = `${progress}%`;
            }, 100);
        }

        // Pause Session
        function pauseSession() {
            sessionActive = false;
            clearInterval(sessionTimer);
            stopHemiSync();
            
            log("Session paused", "warning");
            startBtn.innerHTML = '<i class="fas fa-play"></i> Resume Session';
            startBtn.disabled = false;
            pauseBtn.innerHTML = '<i class="fas fa-play"></i> Session Paused';
        }

        // Reset Session
        function resetSession() {
            sessionActive = false;
            clearInterval(sessionTimer);
            stopHemiSync();
            
            currentFocusLevel = 10;
            updateFocusLevel(10);
            
            sessionTime.textContent = '00:00';
            progressFill.style.width = '0%';
            
            log("Session reset", "info");
            startBtn.innerHTML = '<i class="fas fa-play"></i> Start Session';
            startBtn.disabled = false;
            pauseBtn.innerHTML = '<i class="fas fa-pause"></i> Pause';
            pauseBtn.disabled = true;
            
            // Reset brain visualization
            updateBrainVisualization();
        }

        // Update Session
        function updateSession() {
            if (!sessionStartTime) return;
            
            const elapsed = Date.now() - sessionStartTime;
            const minutes = Math.floor(elapsed / 60000);
            const seconds = Math.floor((elapsed % 60000) / 1000);
            sessionTime.textContent = `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
            
            // Update metrics randomly for simulation
            coherenceValue.textContent = `${Math.floor(70 + Math.random() * 25)}%`;
            stabilityValue.textContent = `${Math.floor(85 + Math.random() * 15)}%`;
            
            // Update AI processing values
            document.getElementById('patternRecognition').textContent = 
                `${Math.floor(70 + Math.random() * 25)}%`;
            document.getElementById('statePrediction').textContent = 
                `${Math.floor(80 + Math.random() * 20)}%`;
            
            updateBrainVisualization();
            updateWaveVisualization();
        }

        // Update Focus Level
        function updateFocusLevel(level) {
            currentFocusLevel = level;
            const focusData = focusLevels[level];
            
            // Update UI
            currentState.textContent = focusData.name;
            stateDescription.textContent = focusData.description;
            brainwaveState.textContent = focusData.brainwave;
            leftFreq.textContent = `${focusData.leftFreq} Hz`;
            rightFreq.textContent = `${focusData.rightFreq} Hz`;
            
            // Update active button
            focusButtons.forEach(btn => {
                if (parseInt(btn.dataset.level) === level) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
            
            // Update audio if session is active
            if (sessionActive) {
                startHemiSync(focusData.leftFreq, focusData.rightFreq);
            }
            
            log(`Transitioned to ${focusData.name}: ${focusData.description}`, "info");
        }

        // Emergency Return Protocol
        function emergencyReturn() {
            emergencyModal.classList.add('active');
            
            let count = 5;
            const countdownInterval = setInterval(() => {
                countdown.textContent = count;
                emergencyProgress.style.width = `${(5 - count) * 20}%`;
                
                if (count <= 0) {
                    clearInterval(countdownInterval);
                    completeEmergencyReturn();
                }
                count--;
            }, 1000);
        }

        // Complete Emergency Return
        function completeEmergencyReturn() {
            resetSession();
            log("Emergency return protocol completed", "success");
            emergencyModal.classList.remove('active');
        }

        // Add Log Entry
        function log(message, type = "info") {
            const logEntry = document.createElement('div');
            logEntry.className = `log-entry log-${type}`;
            
            const now = new Date();
            const timeString = `${now.getHours().toString().padStart(2, '0')}:${now.getMinutes().toString().padStart(2, '0')}:${now.getSeconds().toString().padStart(2, '0')}`;
            
            logEntry.innerHTML = `<span class="log-time">${timeString}</span> ${message}`;
            logContainer.appendChild(logEntry);
            logContainer.scrollTop = logContainer.scrollHeight;
            
            // Keep only last 20 log entries
            const entries = logContainer.querySelectorAll('.log-entry');
            if (entries.length > 20) {
                entries[0].remove();
            }
        }

        // Event Listeners
        startBtn.addEventListener('click', startSession);
        pauseBtn.addEventListener('click', pauseSession);
        resetBtn.addEventListener('click', resetSession);
        emergencyBtn.addEventListener('click', emergencyReturn);
        confirmReturn.addEventListener('click', completeEmergencyReturn);

        focusButtons.forEach(btn => {
            btn.addEventListener('click', () => {
                const level = parseInt(btn.dataset.level);
                updateFocusLevel(level);
            });
        });

        frequencySlider.addEventListener('input', (e) => {
            const delta = parseFloat(e.target.value);
            const focusData = focusLevels[currentFocusLevel];
            
            leftFreq.textContent = `${focusData.leftFreq} Hz`;
            rightFreq.textContent = `${focusData.leftFreq + delta} Hz`;
            
            if (sessionActive) {
                startHemiSync(focusData.leftFreq, focusData.leftFreq + delta);
            }
        });

        // Initialize
        document.addEventListener('DOMContentLoaded', () => {
            initAudio();
            updateFocusLevel(10);
            
            // Start visualization loop
            setInterval(() => {
                updateBrainVisualization();
                updateWaveVisualization();
            }, 50);
            
            log("Project Gateway AI Simulation Lab initialized", "success");
            log("Ready to explore consciousness states", "info");
            log("Select a focus level and start session to begin", "info");
        });

        // Keyboard shortcuts
        document.addEventListener('keydown', (e) => {
            if (e.ctrlKey) {
                switch(e.key) {
                    case ' ':
                        e.preventDefault();
                        if (sessionActive) pauseSession();
                        else startSession();
                        break;
                    case 'r':
                        e.preventDefault();
                        resetSession();
                        break;
                    case 'e':
                        e.preventDefault();
                        emergencyReturn();
                        break;
                }
            }
            
            // Number keys for focus levels
            if (['1', '2', '3', '4'].includes(e.key)) {
                const levels = [10, 12, 15, 21];
                updateFocusLevel(levels[parseInt(e.key) - 1]);
            }
        });

        // Add some sample AI insights after a delay
        setTimeout(() => {
            const insights = [
                "AI Analysis: Neural patterns suggest optimal Focus 10 state achieved",
                "Pattern Recognition: Detecting consistent Theta wave synchronization",
                "Prediction Algorithm: High probability of successful OBE state in 3-5 minutes",
                "Machine Learning: Adapting frequencies based on simulated biometric feedback"
            ];
            
            insights.forEach((insight, index) => {
                setTimeout(() => {
                    log(insight, "success");
                }, index * 5000);
            });
        }, 10000);
    </script>
</body>
</html>
